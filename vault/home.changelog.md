---
id: j36gh6x6yf4u7nuupkcxzn7
title: Changelog
desc: ''
updated: 1652887838716
created: 1652530546551
---

這個頁面放置 Pin 起來 Wiki 的 Changelog。

與部落格的 [Pin 起來的 Changelog](https://pinchlime.com/changelog/) 類似的是，這邊不會放「內容的變化」，而是會放架構、功能等與這個網站有關的變化。

對於版本號，我的定義如下：

- 主版號：表示網站有了大幅度的改版，例如更換架設方式、網域、部署方式等。以我的技術能力來看，應該很長一段時間都會停在版本 1 。
- 次版號：表示網站有新增功能，這邊的功能指的是某些特定欄位、頁面、超連結等，讓讀者可以更好使用、閱讀更多內容的都算是新增功能。
- 修訂號：表示網站既有功能有修改內容，例如 css 樣式的調整、既有頁面或段落的連結調整、或者分類類別的調整等。

以下是依時間倒序排列的 changelogs ，歡迎瀏覽！

---

## To Fix & To Do（之後會想辦法處理的事）

- [ ] 若被首頁連結的頁面，在 backlinks 想要連回首頁時，會出現 404 錯誤，因為首頁的路徑是 https://wiki.pinchlime.com 而不是其他 notes 的聯結路徑。 （2022.05.15）

## [1.3.1] - 2022-05-18

### Changed

- [x] 想把主要頁面的「children」拿掉，避免太多太混亂。（2022.05.18）
    - 今天在 Dendron 的 discord 提問，沒過多久就得到解答：只要把 dendron.yml 裡面的 `enableHierarchyDisplay` 設定為 false 就好了。

---

## [1.3.0] - 2022-05-15

### Added 

- 新增了 [[evergreen]] 的主分類層級。
- 新增了 [[evergreen.workbench]] 這個子分類，放置那些我覺得有機會發展為 Evergreen notes 的零散想法。

### Changed

- 將 What I Learned Today 頁面分拆為 [[daily.what]] 以及 [[daily.how]]。

---

## [1.2.0] - 2022-05-14

### Added

- 開始編輯與更新目前這個 changelog 頁面
- 在 book 這個層級下的每本書都新增 "quotes" 及 "reading notes" 兩種文件，這樣點開個別的書就可以看到 notes & quotes （如果有）。

### Changed

- 將 book 層級改名為 books （第一次使用 Dendron 內建的 Refactor Hierarchy 功能！）

---

## [1.1.0] - 2022-05-08

### Added

- 透過 Netlify 的 [Snippet injection](https://docs.netlify.com/site-deploys/post-processing/snippet-injection/) 功能，在每個頁面放入 GA 追蹤碼。

### Changed

- 透過在 frontmatter 區塊新增 "nav_order" 的資訊，手動排序 nav bar 的排序方式。
- 透過在 dendron.yml 設定「siteHierarchies」，調整 nav bar 會出現的項目及層級。
- 將下列項目都歸類於「daily」這個層級底下：
    - journal
    - book-quotes
    - random-thoughts
    - what-i-found-interesting
    - what-i-learned-today
    - what-i-tried-today
    - daily-why
- 開啟 Dendron 內建的 Github edit 功能，讓使用者可以直接連到每個頁面並發出 pull request。
- 將這個 Wiki 的 Github repository 改為 Public。

---

## [1.0.0] - 2022-05-07

### Added

- Pin 起來的 Wiki 正式上線，網域設定為 https://wiki.pinchlime.com
- 網站透過 Dendron 的 publish 功能輸出，並透過 Netlify 自動部署。
