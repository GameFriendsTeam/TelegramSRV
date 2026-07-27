---

# TelegramSRV

**TelegramSRV** is a lightweight and powerful Minecraft plugin that fully integrates your server with Telegram. Manage your server, sync chat, and receive real-time notifications — all from your favorite messenger.

---

## ✨ Features

- **Chat Sync** — Messages sent in Minecraft appear in Telegram and vice versa
- **Remote Server Control** — Execute console commands directly from Telegram
- **Player Notifications** — Get alerts when players join, leave, or die
- **Advancement Tracking** — Receive notifications when players earn achievements
- **Whitelist Management** — Add or remove players from whitelist via Telegram
- **Server Status** — Check online players, TPS, memory usage, and uptime
- **Fully Configurable** — Custom commands, aliases, messages, and language
- **Lightweight** — Minimal performance impact on your server
- **Permission Support** — Role-based access control for Telegram commands
- **Multi-Language** — Easily translatable message files

---

## 📥 Installation

1. Download the latest `TelegramSRV.jar` from the [Releases](https://github.com/yourusername/TelegramSRV/releases) page
2. Place the JAR file into your server's `plugins/` folder
3. Start your server to generate configuration files
4. Stop the server and edit `plugins/TelegramSRV/config.yml`
5. Add your bot token and chat ID
6. Restart your server — you're all set!

---

## ⚙ Configuration

Create a Telegram bot via [@BotFather](https://t.me/botfather) and get your token. Then configure `config.yml`:

```yaml
bot:
  token: "YOUR_BOT_TOKEN"
  chat-id: "YOUR_CHAT_ID"

settings:
  chat-sync: true
  notify-join: true
  notify-leave: true
  notify-death: true
  notify-advancements: true
  command-prefix: "/"

permissions:
  admin-roles: ["Admin", "Owner"]
  command-whitelist: ["list", "say", "status"]
```

> 💡 **Tip:** To get your chat ID, send a message to your bot and check the server logs, or use `@getmyid_bot`.

---

## 🛠 Commands

### In-Game Commands

| Command | Description |
|---------|-------------|
| `/telegram link <code>` | Link your Minecraft account to Telegram |
| `/telegram reload` | Reload plugin configuration |
| `/telegram help` | Show available commands |

### Telegram Bot Commands (configurable)

| Command | Description |
|---------|-------------|
| `/list` | Show online players |
| `/say <message>` | Send a message as console |
| `/cmd <command>` | Execute any server command |
| `/whitelist add <player>` | Add player to whitelist |
| `/whitelist remove <player>` | Remove player from whitelist |
| `/status` | Show server performance stats |
| `/uptime` | Show server uptime |
| `/help` | List all available commands |

---

## 🔒 Permissions

| Permission | Description |
|------------|-------------|
| `telegramsrv.use` | Allows linking account to Telegram |
| `telegramsrv.admin` | Grants access to all admin commands |
| `telegramsrv.whitelist` | Allows whitelist management via Telegram |
| `telegramsrv.execute` | Allows executing server commands via Telegram |

---

## 🐛 Reporting Issues

Found a bug or have a suggestion? Please [open an issue](https://github.com/yourusername/TelegramSRV/issues) with a clear description and steps to reproduce.

---

## 🤝 Contributing

Contributions are welcome! Feel free to submit pull requests for bug fixes, improvements, or new features. Please ensure your code follows the existing style and includes appropriate tests.

---

## 📜 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

## 🙌 Support

- Join our [Discord](https://discord.gg/ZRtMhswfYj) for community support
- ⭐ Star this repository if you find it useful!

---

**TelegramSRV — Your server, always in your pocket via Telegram.**

---

> **Note:** Replace `yourusername` with your actual GitHub username and update the Discord invite link before publishing.

---
