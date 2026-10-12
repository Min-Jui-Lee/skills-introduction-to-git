<<<<<<< HEAD
# Stack Overflown

一個以程式設計與除錯主題為靈感的瀏覽器方塊消除遊戲。玩家需要排列落下的方塊，將目標中的錯誤圖樣「修正」掉，避免堆疊過高導致遊戲結束。

這個專案結合了經典落下式方塊遊戲的操作感，以及開發者主題的視覺風格，讓你在遊玩時像在處理程式碼錯誤一樣。

## 遊戲特色

- 以程式碼風格設計的遊戲介面
- 5x5 的錯誤模式目標圖樣
- 玩家需透過落下方塊和排列來匹配目標
- 依照成功清除模式加分
- 具備暫停、重玩與遊戲結束狀態
- 無需建置工具，直接用瀏覽器開啟即可玩

## 遊戲玩法

- 每次會產生一個不同形狀的方塊
- 目標區會顯示一個錯誤 pattern（例如 Null Pointer、Memory Leak、Syntax Error 等）
- 當板面上符合這個 pattern 時，該區塊會被清除並加分
- 如果堆疊到頂部，就會觸發遊戲結束

## 控制方式

- 左右鍵：移動方塊
- 上鍵：旋轉方塊
- 下鍵：快速下落
- 空白鍵：直接落下
- P：暫停/繼續

## 專案結構

```text
mod01/
├── README.md
├── LICENSE
├── docs/
│   └── example.md
├── src/
│   ├── index.html
│   ├── index.js
│   ├── patterns.js
│   └── style.css
└── ...
```

## 執行方式

### 方式 1：直接開啟

在瀏覽器中開啟：

```text
src/index.html
```

### 方式 2：使用本機伺服器

```bash
cd mod01
python -m http.server 8000
```

之後在瀏覽器打開：

```text
http://localhost:8000/src/index.html
```

## 主要檔案說明

- `src/index.html`：遊戲畫面與 UI 結構
- `src/style.css`：互動式遊戲樣式與佈局
- `src/patterns.js`：定義錯誤圖樣與目標模式
- `src/index.js`：遊戲邏輯、移動、碰撞檢查與分數判定

## 開發目的

這個專案適合用來練習：

- HTML / CSS / JavaScript 整合
- Canvas 繪圖
- 遊戲邏輯設計
- 碰撞判定與狀態管理
- 前端小型互動專案開發

## License

本專案使用 MIT License。詳細內容請參閱 [LICENSE](LICENSE)。

=======
