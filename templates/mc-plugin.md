![專案的封面圖](#)

# **偉大的麥塊插件**

<center>
    
</center>

[🇹🇼 繁體中文](#) | [🇺🇸 英文](#) | [❓ 其他語言](#)

</center>

![Minecraft Version](https://img.shields.io/badge/Minecraft-1.20.x-green)
![Plugin API](https://img.shields.io/badge/API-Spigot%20%7C%20Paper-blue)
![License](https://img.shields.io/github/license/510208/readme-templates)
![Downloads](https://img.shields.io/badge/下載次數-100%2B-orange)
[![Static Badge](https://img.shields.io/badge/Author-SamHacker-white)](https://github.com/510208)

<details>
<summary>📁 目錄</summary>

- [📦 插件介紹](#-插件介紹)
- [📄 授權條款](#-授權條款)
- [🧰 安裝教學](#-安裝教學)
- [📋 指令清單](#-指令清單)
- [🔐 權限節點](#-權限節點)
- [⚙️ 設定檔說明（`config.yml`）](#%EF%B8%8F-%E8%A8%AD%E5%AE%9A%E6%AA%94%E8%AA%AA%E6%98%8Econfigyml)
- [🙌 感謝名單](#-感謝名單)

</details>

---

## 📦 插件介紹

這是一個用於 [Spigot / Paper] 平台的 Minecraft 插件，提供以下主要功能：

- ✅ 自訂死亡訊息
- ✅ 快捷傳送指令
- ✅ 與 Discord 同步聊天

此插件特別適合：**生存服 / RPG / 建築伺服器** 等類型使用。

---

## 📄 授權條款

本模組透過 MIT 授權條款發布，基於這個條款，你可以基於本條款**重製、修改、合併或出版發行**，但必須在修改後的專案中包含本授權條款、Copyright 等

---

## 🧰 安裝教學

###### 前置需求

- **伺服器**：Paper-Spigot、Spigot、Purpur 與其他插件伺服器
- **前置插件**：
  - PlaceholderAPI
  - Vault
  - Never gonna give you up
- **作業系統**：Debain 系列
- **Java**：17 (任意發行版皆可)
- 沒有**已知的衝突插件**：
  - Never gonna let you down


###### 安裝方式

1. 將下載的 `.jar` 檔案放入伺服器的 `plugins` 資料夾
2. 重新啟動伺服器
3. 檢查是否產生設定檔（如 `/plugins/PluginName/config.yml`）

✅ 支援即時重新加載（使用 `/pluginname reload`）

---

## 📋 指令清單

| 指令                 | 權限節點           | 功能說明           |
| -------------------- | ------------------ | ------------------ |
| `/pluginname`        | `pluginname.use`   | 查看插件狀態與簡介 |
| `/pluginname reload` | `pluginname.admin` | 重新載入設定檔     |

---

## 🔐 權限節點

| 權限節點           | 預設群組 | 功能說明         |
| ------------------ | -------- | ---------------- |
| `pluginname.use`   | 所有人   | 使用基本功能     |
| `pluginname.admin` | OP       | 管理員指令與重載 |

> 可搭配 [LuckPerms](https://luckperms.net/)、[PermissionsEx](https://www.spigotmc.org/resources/permissionsex.108323/) 等權限插件設定。

---

## ⚙️ 設定檔說明（`config.yml`）

```yaml
message-prefix: '&a[插件名稱] '
enable-feature-x: true
cooldown-seconds: 5
```

---

## 🙌 感謝名單

感謝 SamHacker 提供這份模板、xxx 製作本專案、以及所有本專案依賴的元件們。因為有各位的協助，這款專案才能做得出來！

<a href="https://github.com/510208/readme-templates/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=510208/readme-templates" />
</a>
