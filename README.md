---
# CSII Final Project

## 項目簡介

這是清華大學電機系二年級期末專案，實現了一個基於C語言的簡單遊戲項目。該項目包括遊戲邏輯、場景切換、物件管理等功能，展示了C語言在遊戲開發中的應用。

## 特色

- **遊戲邏輯**：實現了鬼魂和角色的移動邏輯。
- **場景切換**：管理遊戲不同場景之間的轉換。
- **物件管理**：包括地圖、物件、場景等元素的管理。
- **跨平台支持**：支援在不同操作系統上編譯和運行。

## 目錄

- [安裝](#安裝)
- [使用方法](#使用方法)
- [文件結構](#文件結構)
- [貢獻](#貢獻)
- [聯絡](#聯絡)

## 安裝

請按照以下步驟來設置和運行項目：

1. 克隆存儲庫：
    ```sh
    git clone https://github.com/cw4real/CSII_finalproject.git
    cd CSII_finalproject
    ```
2. 編譯源代碼：
    ```sh
    gcc -o game Code/*.c
    ```

## 使用方法

1. 運行編譯後的遊戲：
    ```sh
    ./game
    ```
2. 遊戲將自動啟動並進入主選單，按照提示進行操作。

## 文件結構

- `Code/`：存放所有遊戲的源代碼
  - `game.c`：主遊戲邏輯
  - `ghost.c`：鬼魂移動邏輯
  - `map.c`：地圖管理
  - 其他文件：場景和物件管理相關代碼
- `Assets/`：存放遊戲資源文件
- `img/`：存放遊戲相關圖片
- `README.md`：項目說明文件

## 貢獻

歡迎各種形式的貢獻！請提交Issue或Pull Request來貢獻您的改進和建議。

1. Fork此存儲庫
2. 創建您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打開一個Pull Request

## 聯絡

如有任何問題或建議，請通過以下方式聯繫我們：

- GitHub: [cw4real](https://github.com/cw4real)

感謝您對本項目的支持和貢獻！

---
