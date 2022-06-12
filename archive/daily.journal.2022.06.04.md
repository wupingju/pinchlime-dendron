---
id: 3t1dl373fi4khwj37g62lc5
title: '2022-06-04'
desc: ''
updated: 1654359038594
created: 1654358922999
traitIds:
  - journalNote
---

## [[daily.what-i-tried-today]]

### 嘗試在部落格加上 navbar
* 今天比較有空，就來處理 blog to-do list 上面的其中一項：加上 navbar。

* 先研究了 zola 官網的各種 themes ，發現好像都是用 sass 的架構，跟我從 Owen 那邊承襲而來的單純 css 有些落差。所以最後還是看回 Owen 的作法。一開始糾結在他的版本，但後來轉念一想，他放置的地方是在 Section Root ，那我只要放到 Section Top 不就好了？

* 於是經歷了一番亂搞，最後終於製作完成了，整體感覺我還蠻喜歡的，雖然肯定還可以更好，但目前也夠用了。

* 附上截圖 ![](https://pinchlime-screenshots.s3.ap-northeast-1.amazonaws.com/blog-navbar_9OSlVQ.webp)

* 這個研究的過程也讓我開始思考，是不是個人 wiki 還是用 Zola 來建更好？ ^c51wr4g3gw8w

## [[daily.random-thoughts]]

### Dendron 跟 Zola 哪個好？
* 透過 Dendron 建立個人 wiki 剛好滿一個月了，這個月我養成了每天至少提一個問題的習慣，而連帶的好處是我的各種思考更多了，也開始把他們都連在一起。

* 這週開始用更成熟的 Heptabase 來實踐這個習慣，發現也非常順手，甚至因為圖像化的連結，比 Dendron 更勝一籌。這也讓我想起，既然 Dendron 在實踐習慣這一環已經不需要了，那在 Publish 這環是否也有必要維持呢？

* 曾被淘汰的 Logseq Publish 就先暫且不論，我想比較的是拿來寫部落格的 Zola 。

* Zola 的優點是，部署極快，網站跑起來也極快，而且隨著我四月那波認真玩的經驗，我對於自己的整個 zola site 裡面的各項程式碼有一定的了解程度，這樣的了解一方面是了解「Zola 可以辦到什麼」，另一方面則是了解「我還無法透過 Zola 辦到什麼」。

* 我無法辦到的是像 Dendron 那樣內建的階層架構以及資料夾的呈現方式（但可以學習命名方式），我也無法辦到 Dendron 方便地建立雙向連結。（但若只是把 Hepta 裡整理好的資訊更新上去，則有機會手動辦到。

* 所以看起來，Hepta 補足了 Zola 這種單純的 SSG 在管理知識系統上的功能缺陷，那這樣看起來就更有使用 Zola 的理由了。 ^skomf5m4kkms