## Add Flex Superpowers to the Tweet Embed

Di sebelah kanan adalah embed tweet yang akan digunakan sebagai contoh praktis. Beberapa elemen akan terlihat lebih baik dengan tata letak yang berbeda. Tantangan terakhir menunjukkan tampilan: fleksibel. Di sini Anda akan menambahkannya ke beberapa komponen di tweet embed untuk mulai menyesuaikan pemosisiannya.



Tambahkan tampilan properti CSS: fleksibel untuk semua item berikut - perhatikan bahwa pemilih sudah diatur dalam CSS:



header, header .profile-name, header .follow-btn, header h3 dan h4, footer, dan footer .stats footer.



Soal :

1. Header Anda harus memiliki properti tampilan yang disetel melenturkan / flex.
2. Footer Anda harus memiliki properti tampilan yang disetel melenturkan / flex.
3. H3 Anda harus memiliki properti tampilan yang disetel melenturkan / flex.
4. H4 Anda harus memiliki properti tampilan yang disetel melenturkan / flex.
5. Nama .profile Anda harus memiliki properti tampilan yang disetel agar fleksibel.
6. Anda .follow-btn harus memiliki properti tampilan yang disetel melenturkan / flex.
7. Anda .stats harus memiliki properti tampilan diatur untuk melenturkan / flex.

Jawaban :

```
<style>
  body {
    font-family: Arial, sans-serif;
  }
  header {
    display: flex;
  }
  header .profile-thumbnail {
    width: 50px;
    height: 50px;
    border-radius: 4px;
  }
  header .profile-name {
    display: flex;
    margin-left: 10px;
  }
  header .follow-btn {
    display: flex;
    margin: 0 0 0 auto;
  }
  header .follow-btn button {
    border: 0;
    border-radius: 3px;
    padding: 5px;
  }
  header h3, header h4 {
    display: flex;
    margin: 0;
  }
  #inner p {
    margin-bottom: 10px;
    font-size: 20px;
  }
  #inner hr {
    margin: 20px 0;
    border-style: solid;
    opacity: 0.1;
  }
  footer {
    display: flex;
  }
  footer .stats {
    display: flex;
    font-size: 15px;
  }
  footer .stats strong {
    font-size: 18px;
  }
  footer .stats .likes {
    margin-left: 10px;
  }
  footer .cta {
    margin-left: auto;
  }
  footer .cta button {
    border: 0;
    background: transparent;
  }
</style>
<header>
  <img src="https://pbs.twimg.com/profile_images/378800000147359764/54dc9a5c34e912f34db8662d53d16a39_400x400.png" alt="Quincy Larson's profile picture" class="profile-thumbnail">
  <div class="profile-name">
    <h3>Quincy Larson</h3>
    <h4>@ossia</h4>
  </div>
  <div class="follow-btn">
    <button>Follow</button>
  </div>
</header>
<div id="inner">
  <p>I meet so many people who are in search of that one trick that will help them work smart. Even if you work smart, you still have to work hard.</p>
  <span class="date">1:32 PM - 12 Jan 2018</span>
  <hr>
</div>
<footer>
  <div class="stats">
    <div class="Retweets">
      <strong>107</strong> Retweets
    </div>
    <div class="likes">
      <strong>431</strong> Likes
    </div>
  </div>
  <div class="cta">
    <button class="share-btn">Share</button>
    <button class="retweet-btn">Retweet</button>
    <button class="like-btn">Like</button>
  </div>
</footer>
```



