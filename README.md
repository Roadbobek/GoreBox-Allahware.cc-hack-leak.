# GoreBox Mod Allahware.cc Installation Guide (BepInEx)

> ⚠️ **Disclaimer:** This guide is intended strictly for educational and legitimate modding purposes. We do **not** support or promote game hacking, cheating, or the use of pirated or leaked software. Always respect the game's terms of service and community guidelines.

---

## 📦 Requirements

- [BepInEx (Unity IL2CPP for Windows x64)](https://builds.bepinex.dev/projects/bepinex_be)
- A compiled `.dll` mod plugin
- Windows operating system (x64)
- GoreBox (latest version)

---

## 🧰 Step 1: Download BepInEx

1. Visit the [BepInEx bleeding edge builds page](https://builds.bepinex.dev/projects/bepinex_be).
2. Download the latest release of this hack (.dll)
3. Save and extract the contents of the downloaded `.zip` file.

---

## 🗂 Step 2: Install BepInEx

1. Open the folder where **GoreBox.exe** is installed.
- For Steam: Right-click GoreBox in your Library → Manage → Browse local files.
2. Extract the contents of the BepInEx `.zip` into this folder.
3. After extraction, your game folder should look like this:
GoreBox/
├── BepInEx/
├── doorstop_config.ini
├── winhttp.dll
└── GoreBox.exe

yaml
Copy
Edit

---

## 🧩 Step 3: Install Your Mod Plugin

1. Inside the game folder, open:2. Place your mod `.dll` file inside this folder.
- Example:
  ```
  GoreBox/BepInEx/plugins/MyCoolMod.dll
  ```

---

## 🚀 Step 4: Launch the Game

- Launch GoreBox normally (via Steam or executable). Make sure your using Direct x11 `Force D3D11`
- BepInEx will automatically initialize and load all plugins in the `plugins` folder.
- If your mod uses a keybind (e.g., `F9`), press it in-game to activate the mod UI or features.

---

## 🔐 Optional: PlayFab Custom ID & Ban Bypass Setup

> **Use this feature responsibly. Intended for private/offline development and testing.**

1. In-game, open the **PlayFab** menu.
2. Set:
- **Custom ID**: any string (e.g., `TestUser123`)
- **Nickname**: any display name
3. Enable **Bypass Ban** using any of the available working options:
- ✅ Grocery (Working)
- ✅ Yagiz (Working)
- ❌ Bxdev (Not working currently)
4. Enable **Antikick**:
- Turn it **on before joining** a server.
- Turn it **off before leaving** a server.
- Turn it **off before clicking** multiplayer

---

## 📎 Useful Links

- 🔗 [Download BepInEx (Unity IL2CPP x64)](https://builds.bepinex.dev/projects/bepinex_be)
- 📘 [BepInEx Official Documentation](https://docs.bepinex.dev/)
- 🛠 [GoreBox on Steam](https://store.steampowered.com/app/2027330/GoreBox/)
- 💬 [BepInEx GitHub Repository](https://github.com/BepInEx/BepInEx)

---

## ✅ Tips & Troubleshooting

- ❗ **DLL not loading?**
- Right-click the `.dll` file → Properties → Check “Unblock” (if available).
- 🔒 Run the game as **Administrator** if mods don’t load.
- 🧾 Check `BepInEx/LogOutput.log` for errors or plugin load messages.
- 🔄 Restart the game after installing a new plugin.

---

## ⚠️ Legal Notice

This guide is not affiliated with, endorsed by, or connected to the developers of GoreBox or any modding tools mentioned. Always mod responsibly and follow all local laws and platform terms of service.

