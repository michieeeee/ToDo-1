# ToDoリスト1

HTML・CSS学習用のモダンなToDoリストです。基礎的なWeb技術の理解を深めるための教材として作成しました。

## 学習目的

### HTML学習要素
- **セマンティックHTML**: `<header>`, `<main>`, `<section>`, `<footer>`の使い方
- **基本要素**: `<ul>`, `<li>`, `<input>`, `<label>`, `<button>`の構造化
- **属性**: `id`, `class`, `for`属性による要素の関連付け

### CSS学習要素

#### セレクタの種類
- **要素セレクタ**: `body`, `ul`, `li`など
- **IDセレクタ**: `#main-title`, `#main-container`
- **クラスセレクタ**: `.todo-category`, `.task-item`, `.task-label`
- **疑似クラス**: `:hover`, `:checked`, `:focus`, `:last-child`

#### 主要プロパティ
- **レイアウト**: `display: grid`, `flex`, `margin`, `padding`
- **装飾**: `background`, `border`, `border-radius`, `box-shadow`
- **タイポグラフィ**: `font-family`, `font-size`, `font-weight`
- **アニメーション**: `transition`, `transform`

#### レスポンシブデザイン
- **CSS Grid**: `grid-template-columns`, `auto-fit`, `minmax()`
- **メディアクエリ**: `@media (max-width: 768px)`
- **モバイルファーストアプローチ**

## デザイン特徴

### ビジュアル効果
- **グラデーション背景**: `linear-gradient()`でモダンな見た目
- **カード式レイアウト**: 各カテゴリを独立したカードとして表示
- **カテゴリ別色分け**: 
  - 仕事: 青系 (`#3498db`)
  - プライベート: 緑系 (`#2ecc71`) 
  - 買い物: オレンジ系 (`#f39c12`)

### インタラクション
- **ホバー効果**: カードとボタンの浮き上がり効果
- **チェック済みスタイル**: 取り消し線と透明度変更
- **フォーカス表示**: アクセシビリティを考慮したフォーカス枠

## ファイル構成

```
.
├── README.md
├── todo_list.html    # メインのHTMLファイル
└── styles.css        # CSSスタイルファイル
```

## 使い方

1. `todo_list.html`をブラウザで開く
2. チェックボックスをクリックしてタスクの完了状態を切り替え
3. レスポンシブ確認のため、ブラウザウィンドウサイズを変更してみる

## 学習ポイント

このプロジェクトを通して以下が学べます：

- **HTML構造化**: セマンティックな要素の適切な使用
- **CSSセレクタ**: 様々なセレクタの実践的な使い方  
- **レスポンシブ**: モバイル対応の基本的な考え方
- **UI/UX**: ユーザビリティを考慮したデザイン設計