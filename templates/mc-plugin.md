![專案的封面圖](#)

# **偉大的麥塊插件**

![Minecraft Version](https://img.shields.io/badge/Minecraft-1.20.x-green)
![Plugin API](https://img.shields.io/badge/API-Spigot%20%7C%20Paper-blue)
![License](https://img.shields.io/github/license/你的帳號/插件名稱)
![Downloads](https://img.shields.io/badge/下載次數-100%2B-orange)

---

## 📦 插件介紹

這是一個用於 [Spigot / Paper] 平台的 Minecraft 插件，提供以下主要功能：

- ✅ 功能一（如：自訂死亡訊息）
- ✅ 功能二（如：快捷傳送指令）
- ✅ 功能三（如：與 Discord 同步聊天）

此插件特別適合：**生存服 / RPG / 建築伺服器** 等類型使用。

---

## 🧰 安裝方法

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
