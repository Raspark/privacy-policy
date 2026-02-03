# Polify

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Flutter](https://img.shields.io/badge/platform-Flutter-02569B?logo=flutter)

**Polify** 是一款為極簡主義者設計的政策與新聞閱讀應用。我們移除多餘的視覺干擾，讓閱讀回歸純粹。

**Polify** is a policy and news reading application designed for minimalists. We remove visual clutter to bring back the purity of reading.

---

## ✨ 核心功能 Features

* **極簡介面 Minimalist UI**：採用 300 字重纖細字體與大量留白美學。
* **本地儲存 Local Storage**：使用 Hive 數據庫實現秒開的收藏與離線閱讀。
* **觸覺回饋 Haptic Experience**：深度整合 Flutter HapticFeedback，提供細膩的操作手感。
* **多語言支持 Dual Language**：完美支援中英文切換與適配。
* **隱私至上 Privacy First**：不收集個人識別資料，數據僅儲存在您的裝置中。

---

## 🛠️ 技術棧 Tech Stack

本 App 基於 **Flutter** 框架開發，使用了以下關鍵技術：
This App is built with **Flutter** and leverages the following technologies:

* **持久化 (Persistence)**: `Hive`, `SharedPreferences`
* **網路 (Networking)**: `http`, `xml` (RSS Parsing)
* **分析 (Analytics)**: `Firebase Core`
* **工具 (Utilities)**: `intl` (Localization), `url_launcher`, `share_plus`
* **震動回饋 (Feedback)**: `HapticFeedback` (Flutter Services)

---

## 🚀 快速開始 Getting Started

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Raspark/polify.git](https://github.com/Raspark/polify.git)
