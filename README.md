# 🚀 IWWI – Meteor Addon for DonutSMP (v1.21.5)

Welcome to **IWWI** – the ultimate strategic automation addon built for the [Meteor Client](https://meteorclient.com/) on **Minecraft 1.21.5**, specifically designed for **DonutSMP**. Dominate the underground meta, manage your resources with precision, and stay 10 steps ahead of your enemies!

> ⚠️ Requires Meteor Client 1.21.5 and Baritone for some features  
> 🌐 Supports optional **Discord Webhook** notifications for key modules

---

## 🧩 Modules

### ⛏️ AutoMineDownRTP
Automatically **RTPs** and mines straight down to Y = **-5** in search of hidden bases and player stashes.  
Perfect for discovering underground vaults in new chunks.

---

### 💣 AutoSpawnerBreakerBaritone *  
Uses **Baritone** to navigate to and **break all spawners** in your base for security.  
When a player is detected nearby, the module automatically **logs you out**, keeping your location safe.

> 🔔 **Supports Discord Webhook notifications**

---

### 📦 AutoSpawnerChestClicker
Automates the tedious process of **collecting bones** from your mob spawner chest and delivering them to a target chest.  
Maximize efficiency with zero manual effort!

---

### 🧱 BlockESP *  
Highlights user-specified blocks in the world, making them visible through walls.  
Ideal for finding **spawners, chests, ores**, and more while mining or exploring.

> 🔔 **Supports Discord Webhook notifications**

---

### 🛫 AutoElytraFlight *  
Automated Elytra flying with smooth, airplane-style **takeoff and landing** mechanics.  
Can fly long distances across terrain, oceans, or nether tunnels without crashing into the void.

> 🔔 **Supports Discord Webhook notifications**

---

### 🎒 StashFinder *  
Scans and logs the presence of **hidden stashes** such as chest clusters and shulkers.  
When a stash is found, you’ll get a ping on your configured webhook.

> 🔔 **Supports Discord Webhook notifications**

---

### 🪓 MineToYMinus50
A simple but effective module that tunnels you straight to **Y = -50**, commonly used base depth.  
Can help uncover bedrock-layer vaults or trap setups.

---

## 🔧 Setup & Installation

1. 📥 Download the latest build of **IWWI** from the [official website](http://iwwi.info) tab.
2. Move the `.jar` file to your `.minecraft/mods` folder
3. (Optional) Configure your **Discord Webhook URL** in the settings of modules marked with `*` for remote notifications.
4. Launch Minecraft 1.21.5 with Meteor Client + Baritone and enjoy!

---

### 🤝 AutoTPA/TPAHere
Automates the process of sending repeated **/tpa** or **/tpahere** requests to a specified player.  
Configure the target nickname, delay between requests, and command type. The module will send 15 requests in rapid succession (with your chosen delay), pause for 2–6 seconds, and repeat the cycle until deactivated.  

> **❗ Note:** On DonutSMP, you must **disable TPA confirm menus** in your server settings for this module to work automatically.

---

## 💬 Webhook Integration

Set up a Discord webhook in a private channel to receive notifications from:

- AutoSpawnerBreakerBaritone
- BlockESP
- AutoElytraFlight
- StashFinder

These alerts will keep you updated on in-game activity even when you're AFK or offline.

---

## 📜 License

This project is released under the **GNU General Public License v3.0**.

---

Stay hidden. Stay automated.  
Welcome to **IWWI**.

