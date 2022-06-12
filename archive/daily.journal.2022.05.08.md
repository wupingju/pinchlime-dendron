---
id: h5e7ffb58vexcvmmg9tdcfk
title: '2022-05-08'
desc: ''
updated: 1653709362830
created: 1651984755552
traitIds:
  - journalNote
---

## [[daily.how]]

### 如何在 Dendron 發布時自訂排序？

- 可以在 dendron.yml 裡面設定 siteHierarchies ，把 root 改成自己想要的階層。
- 可以在個別文件的 yaml 欄位設定 "nav_order" 來改變在導覽列的排序，我透過這功能把 Daily 裡面的 Journal 改到第一個，其他項目則排在下方。 ^oycs7ac882m7

## [[daily.random-thoughts]]

### Dendron 的優點 - 兼顧層級化的架構以及彈性

層級化的優點可以參考 Dendron 創辦人 Kevin S Lin 在[A Hierarchical Tool for Thought](https://www.kevinslin.com/notes/127a3230-4484-433a-b97f-178679564207/)裡面的這段文字：

> 
1. You can create, find, update, search, and remove information by looking up their hierarchies.
2. You can remember your hierarchies with schemas, custom metadata to describe and enforce the shape of your hierarchies.
3. You can transform your hierarchies, either a single note or an entire hierarchy at a time.
4. You can combine hierarchies with other constructs like tags, backlinks, and note references.
5. You can capture chronological as well as ad-hoc information using Dendron's builtin hierarchies
6. You can visualize your hierarchies through hierarchical graph views
7. You can share any subset of your hierarchy as a published site.
8. You can move your notes and their hierarchy to any other tool.

但層級化架構的問題在：一個筆記不一定只出現在一個地方，因此過早思考他的「層級」與「位置」可能會讓使用者感到阻力。

對於這種是否選擇層級化的兩難，我覺得透過「Daily Journal/notes」這種固定的格式來紀錄是個好方法。

從整個筆記庫的架構來看，Daily Journal 本身就是一個僵固的類別，層級與位置不需要動腦就可以產生。

但以個別筆記來說，Journal 裡的內容仍可以擁有彈性，並且可以透過 tags, backlinks 以及 embed notes （在 Dendron 裡面叫做 note references）來達成交互參照以及讓同一筆記出現在不同地方的需求。 ^0zk9wjyrtze0

### [[books.你會問問題嗎]]

#### 嘗試將肯定句後面加上問號
- 在看 [[books.你會問問題嗎]] 的時候，有提到一小段有趣的建議：將某些章節標題的肯定句改寫成問句，光是這件事就會更加促進我們思考，並且可以從原先的章節裡面學到更多（或懷疑更多）。

#### 應該區分問題是 Why、How 還是 What
- 快速看完前兩章，最後一段都有提供 10 個跟該章節有關的「問題思考」，我想了一下最想回答的問題只有「我會對什麼人提出問題？為什麼？」結果轉念一想發現，這 20 個問題裡面只有這是一個「Why」的問題。
- 好像慢慢感覺到問「Why」型問題的好處，這類型的問題不是從自己既有的資訊或想法去檢索答案，而是朝未知的地方探索。有了這個想法後，更加覺得應該努力實踐每天更新 [[daily.why]] 了。 ^5q2ip6x70wze

## [[daily.why]]

### 我會對怎樣的人提問？為什麼？
- 對知道我不知道的事情的人，例如在嘗試新工具或學習新技術時，詢問有分享過經驗或想法的人，因為我覺得向他們學習更有效率。（但這些比較屬於 How 的問題）
- 針對我在意的事情向人提問，通常會在這件事的發展與我預期不符時發生（超出預期時會問怎麼辦到的，低於預期時會問「為什麼會這樣」）
- 但問「為什麼會這樣」容易有責罵感，可能需要換個方式問，例如：「是發生了什麼意料之外的狀況嗎？」

### 為什麼我不想把部落格或 wiki 開源？
- 之前在架好[部落格](https://pinchlime.com)時曾經有想過要不要將完整的內容開源（我的理解是把整個 repository 改為 Public 的意思），但當時有點下意識地抗拒這件事，因此本次在建立 wiki 時也是先採用 private repository 。
- 我覺得抗拒的點好像是擔心「自己在 zola 亂改的程式碼可能會被笑、可能誤導人」，但坦白說，這個擔憂寫出來也覺得很好笑，因為我大可以寫下一些免責聲明或者指引。
- 但今天突然覺得可以嘗試把這個 wiki 開源，第一個原因是這好像更貼近 Learn in public 的感覺。第二個原因是， Dendron 就內建了每個頁面的固定連結，可以讓使用者在 Github 編輯。雖然我對開源還超不熟，不知道可以怎麼用，但覺得或許可以試試看。
- 因此我把這個 wiki site 改成 public 了，網址在這： [https://github.com/wupingju/pinchlime-dendron](https://github.com/wupingju/pinchlime-dendron)。 ^s8py4mo7ci2i
