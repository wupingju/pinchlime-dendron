---
id: dec7hlvy610sol126ys3s4o
title: '2022-05-07'
desc: ''
updated: 1651941266381
created: 1651940225917
traitIds:
  - journalNote
---

## [[daily.daily-why]]

### 為何技術文件很容易過時？
- 今天在透過 Dendron 的官方文件學習 publish 功能時，走了不少彎路，一直卡在一個 bug 裡面，後來我幾乎是逐步驟測試，才發現出現問題的步驟是什麼。
- 想起之前在學習透過 Zola 部署網站時，也發現文件上的內容看起來已經有點過時了。
- 我還沒有維護過面向客戶的技術文件，所以不確定這件事的**本質原因**可能會是什麼。表層的原因可能是資源不足，或者覺得這件事沒那麼重要，但流程上是否有改善的空間？現行的工具有沒有適合拿來處理這個問題的？
- 希望以後的自己有能力回答這些問題。 ^8gir3mijqw25


## [[daily.what-i-learnt-today]]

### Dendron 輸出靜態網站到 Netlify 的方式
- 今天一整天都在嘗試使用 Dendron 建構目前看到的這個網站，詳細的步驟之後再來分享，中間遇到了好幾次障礙，差點想放棄。
- 在這邊簡單描述一下整件事的概念，其實跟之前在部落格寫的 [Pin 起來改版了！從 Wordpress 搬家到 Zola！](https://pinchlime.com/blog/rebuilt-pinchlime/) Zola 部署概念很像。
- 在 Dendron 資料的根目錄裡面，配置好 `Netlify.toml` 以及依照[官網教學文件](https://wiki.dendron.so/notes/yetuum6o9wZi6eVJQBbQb/)建立的 `dendron-publish-site.sh` 文件後，就可以在 Netlify 裡面直接抓取整個 repository ，並且進行自動部署。
- 換句話說，未來的自動部署也不一定要透過桌面版的 Dendron 進行，只要 repository 有變動， Netlify 就會自動部署差異的內容。
- 這點跟 Zola 的部署方式很像，差異可能在客製化程度以及部署的時間，但兩者類似的流程讓我可以用類似的工具來經營，覺得這是很棒的事。 ^ebpe1ehqt68x