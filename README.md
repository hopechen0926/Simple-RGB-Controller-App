# Simple RGB Controller App

這是一個使用 SwiftUI 開發的簡易 RGB 控制器 App，透過三個滑桿調整紅、綠、藍三原色的比例，即時改變背景顏色，並顯示目前的 RGB 數值。

## 功能介紹

- 實時背景顏色調整（基於 RGB 值）
- 三個滑桿分別控制 R / G / B 數值（範圍 0 ~ 255）
- 動態文字顯示當前 RGB 數值
- 介面簡潔直觀，適合學習 SwiftUI 基礎

## 專案結構

```
.
├── ContentView.swift # 主視圖，包含 RGB 控制邏輯與 UI
├── ShowWords.swift # 顯示 R/G/B 數值的自訂元件
├── README.md # 本說明文件
```

## 使用方式

1. 開啟 `Xcode`
2. 使用 SwiftUI 預覽或模擬器執行 App
3. 拖動紅、綠、藍三個滑桿，觀察背景顏色變化與 RGB 值更新

## 開發工具

- Swift 5+
- SwiftUI
- Xcode 12 或以上版本建議使用
