# ☄️ Meteor Client — Version Compatibility & Installation Guide

A clean and organized overview of **Meteor Client** versions matched with their corresponding **Minecraft** releases, along with a step-by-step Fabric installation guide.

---

## 📊 Version Compatibility Table

| Meteor Client Version | Minecraft Version | Required Loader |
| :---: | :---: | :---: |
| **`0.5.8`** | `1.21.1` | Fabric Loader |
| **`0.5.7`** | `1.20.6` | Fabric Loader |
| **`0.5.6`** | `1.20.4` | Fabric Loader |
| **`0.5.5`** | `1.20.2` | Fabric Loader |
| **`0.5.4`** | `1.20` / `1.20.1` | Fabric Loader |
| **`0.5.3`** | `1.19.4` | Fabric Loader |
| **`0.5.2`** | `1.19.3` | Fabric Loader |
| **`0.5.1`** | `1.19.2` | Fabric Loader |
| **`0.5.0`** | `1.19` | Fabric Loader |

---

## 🛠️ Step-by-Step Installation Guide

### Step 1: Install Fabric Loader
1. Download the **Fabric Installer** from the official website ([fabricmc.net](https://fabricmc.net/)).
2. Run the downloaded installer file (`.exe` or `.jar`).
3. Select the exact Minecraft version you want to play (matching the compatibility table above) and click **Install**.

### Step 2: Download Required Files
1. Download the matching **Meteor Client** version from the official source.
2. Download the corresponding **Fabric API** mod for your targeted Minecraft version (available on Modrinth or CurseForge).

### Step 3: Place Mods in the Game Directory
1. Open the Run dialog using the key shortcut `Win + R`.
2. Type `%appdata%\.minecraft` and press **Enter**.
3. Open the `mods` folder (if it doesn't exist, create a new folder named `mods`).
4. Copy and paste both downloaded `.jar` files (**Meteor Client** and **Fabric API**) into the `mods` folder.

### Step 4: Launch Minecraft
1. Open the official **Minecraft Launcher**.
2. Select the newly created **Fabric Loader** profile corresponding to your Minecraft version.
3. Launch the game. Once inside, press **Right Shift** to open the in-game Meteor Client GUI menu.

---

## 💡 Useful Tips
- **ViaFabric / ViaVersion:** To connect to servers running on different versions than your installed client, place the **ViaFabric** mod into your `mods` folder.
- **Configurations:** All client configs, HUD layouts, and macros are stored in `.minecraft/meteor-client`. You can easily back up or share this directory.
