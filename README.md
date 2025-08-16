# 🎮 Minecraft CCI Stream Setup

This repo shares my **Content Creator Integration (CCI)** setup for **Minecraft 1.20.1 (Forge 47.4.0)**, used on my Twitch channel **[llorenzo_exe](https://twitch.tv/llorenzo_exe)**.  

It helps streamers connect **StreamElements events** to in-game actions, like spawning sheep, cats, or zombie hordes with viewers' names! 🐑💥  

👉 My goal is to make it easy for you to set up CCI and bring your streams to life.  
Follow the guide below, copy my events, and start creating epic Minecraft moments!  

⚠️ **Note:** All chat messages are currently in **Italian**. You can change them very easily in the config.

---

## 📜 My Stream Events

- **Follow** → Spawns 1 sheep named after the follower.  
- **Subscription (1 month)** → Spawns 1 cat named after the subscriber, tamed to *llorenzo_exe*.  
- **Gifted Sub / Donation (100 bits = 1€):**  
  - 5€ / 500 bits → 5 zombies + 3 skeletons  
  - 10€ / 1000 bits → 7 zombies + 5 skeletons + 1 witch  
  - 25€ / 2500 bits → 10 zombies + 7 skeletons + 2 witches + 1 blaze  
  - 50€ / 5000 bits → 15 zombies + 10 skeletons + 3 witches + 3 blazes + 3 wither skeletons  
- **Raid or Host** → 1 zombie per viewer (up to 50), named after the streamer who raided or hosted  

---

## 🛠️ Setup Guide

### Requirements
- Minecraft **1.20.1** with **Forge 47.4.0** ([download](https://files.minecraftforge.net/))  
- [CCI mod (CurseForge)](https://www.curseforge.com/minecraft/mc-mods/content-creator-integration)  
- StreamElements account with a **JWT token**  
- A world with **cheats enabled**

### Steps

1. **Install CCI**  
   - Download CCI for Minecraft 1.20.1  
   - Place the `.jar` in `.minecraft/mods/`

2. **Create a World**  
   - Start a singleplayer world with **Allow Cheats: ON**

3. **Connect StreamElements**  
   - Follow the official guide: [CCI Docs](https://content-creator-integration.readthedocs.io/en/latest/gettingstarted/)  
   **OR**  
   - Get your JWT token from **StreamElements Dashboard > Profile > Show secrets**  
   - Edit `.minecraft/config/contentcreatorintegration.toml`:

   [socket]
   streamElementsTokens = ["your_jwt_token_here"]
   streamElementsWebsocketTokens = ["your_jwt_token_here"]

---

## 🐞 Troubleshooting

* ❌ No mobs? → Ensure **cheats are enabled** in your world.
* ❌ No events? → Verify the **StreamElements token** and **WebSocket** in `/cci edit > Connections`.
* ❌ Errors? → Check `.minecraft/logs/latest.log`.

---

## 🤝 Contribute

Have a cool CCI setup?
Share it in **GitHub Discussions** or on my **Twitch**!
Let’s make streaming better together! 🌟

---

## 😎 Support

If this helped you, drop by my Twitch channel and maybe spawn a sheep or two! 🐾
⭐ **Star this repo** to share with others!

---

## 📜 License

[MIT License](./LICENSE)

---

## 👤 Created by

* **Discord:** .lorenzo_.
* **Instagram:** [llorenzo\_exe](https://www.instagram.com/llorenzo.exe/)
* **Twitch:** [llorenzo\_exe](https://twitch.tv/llorenzo_exe)
