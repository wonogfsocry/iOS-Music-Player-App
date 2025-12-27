# 🎵 iOS Music Player App (01157025Music_App)

這是一個使用 **SwiftUI** 和 **AVFoundation** 框架構建的 iOS 音樂播放器應用程式。它提供了一個現代化的使用者介面，支援背景播放、歌曲切換、隨機播放、循環模式以及進度條拖曳等完整功能。

## 📱 介面預覽 (Interface Preview)

<div align="center">
  <img src="<把你的圖片連結放這裡>" alt="App Interface" width="300" />
</div>

> *系統介面展示：包含播放控制、歌曲封面與動態背景。*

## 🔗 相關連結 (Links)

* **專案詳解文章**：[點擊閱讀 Medium 文章](<https://medium.com/%E6%B5%B7%E5%A4%A7-ios-app-%E7%A8%8B%E5%BC%8F%E8%A8%AD%E8%A8%88/ios%E6%87%89%E7%94%A8%E7%A8%8B%E5%BC%8F%E9%96%8B%E7%99%BC%E5%85%A5%E9%96%80-%E5%8A%A0%E5%88%86%E4%BD%9C%E6%A5%AD-%E9%9F%B3%E6%A8%82%E6%92%AD%E6%94%BE%E5%99%A8-b6e71a1364ca>)

---

## ✨ 主要功能 (Features)

* **基礎播放控制**：支援 播放 (Play) / 暫停 (Pause) / 上一首 (Previous) / 下一首 (Next)。
* **進度控制**：
    * 顯示當前播放時間與總時間。
    * 支援拖曳進度條 (Slider) 進行快轉或倒退 (Seeking)。
* **音量調節**：內建音量滑桿，可直接調整應用程式內的播放音量。
* **播放模式**：
    * 🔀 **隨機播放 (Shuffle)**：隨機選擇下一首歌曲。
    * 🔁 **循環模式 (Repeat)**：支援三種模式切換：
        * `Off` (不循環)
        * `All` (循環播放列表)
        * `Single` (單曲循環)
* **歌曲清單**：點擊清單按鈕可開啟歌曲列表，快速選擇並切換歌曲。
* **精美 UI**：包含背景圖片、歌曲封面顯示以及動態的按鈕狀態。

## 🎧 收錄歌曲 (Track List)

本專案目前收錄了 **Vaundy** 的多首熱門歌曲：

1.  呼吸のように
2.  裸の勇者
3.  踊り子
4.  不可幸力
5.  東京フラッシュ
6.  CHAINSAW BLOOD

## 🛠 技術規格 (Tech Stack)

* **語言**：Swift 5
* **框架**：SwiftUI
* **音訊處理**：AVFoundation (使用 `AVPlayer` 與 `AVPlayerItem`)
* **開發工具**：Xcode 16.0+
* **目標系統**：iOS 18.0+

## 📱 安裝與執行 (Installation)

1.  確認你的 Mac 已安裝 **Xcode 16** 或更高版本。
2.  下載或複製本專案資料夾。
3.  雙擊 `01157025Music_App.xcodeproj` 開啟專案。
4.  選擇模擬器 (如 iPhone 16) 或連接實體裝置。
5.  按下 `Cmd + R` 或點擊 Xcode 左上角的 **Run** 按鈕進行編譯與執行。

## 📖 程式碼結構 (Code Structure)

* **`_1157025Music_AppApp.swift`**: 應用程式的進入點。
* **`ContentView.swift`**: 包含主要的 UI 視圖與邏輯。
    * `MusicPlayerView`: 主播放器介面，處理播放邏輯 (`AVPlayer`)、狀態管理 (`@State`) 與 UI 配置。
    * `TrackListView`: 歌曲清單視圖，使用 `NavigationView` 和 `List` 呈現。
    * `CircleButton`: 自定義的圓形按鈕元件。
    * `RepeatMode`: 定義循環模式的列舉 (Enum)。

## 📝 作者 (Author)

* **Student ID**: 01157025
* **Created Date**: 2025/1/3
