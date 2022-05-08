---
id: h5e7ffb58vexcvmmg9tdcfk
title: '2022-05-08'
desc: ''
updated: 1652007465446
created: 1651984755552
traitIds:
  - journalNote
---

## [[daily.what-i-learned-today]]

### Dendron 的自訂排序功能
- 可以在 dendron.yml 裡面設定 siteHierarchies ，把 root 改成自己想要的階層。
- 可以在個別文件的 yaml 欄位設定 "nav_order" 來改變在導覽列的排序，我透過這功能把 Daily 裡面的 Journal 改到第一個，其他項目則排在下方。 ^fjq3gmw4da95

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

