# LuaGen – Free Lua Generator for Steam Games

LuaGen is a **free and ad-free Lua file generator** for Steam games. By entering a Steam Game ID, you can instantly generate and download verified Lua archives for thousands of popular games.

---

## 🚀 Why LuaGen?

* **⚡ Instant Downloads** – No waiting, files are ready in seconds.
* **🎮 Huge Collection** – Access to **32,000+ verified Lua archives**.
* **🛡️ Safe & Verified** – All files are scanned and community-tested.
* **📂 Backup System** – If the primary server is unavailable, a GitHub-hosted backup is provided.
* **🌐 Fast Delivery** – Hosted on **Cloudflare Pages + optimized CDN storage** for ultra-fast response times.

---

## 🔧 How It Works

1. Enter a valid **Steam Game ID**.
2. LuaGen checks our **primary CDN storage** to see if a `.zip` archive exists.
3. If found → instant download.
4. If not found → fallback backup download is provided via GitHub.
5. Done! 🎉

This architecture makes LuaGen **fast, lightweight, and reliable**.

---

## 📦 Installation Guide

1. **Download & Extract** – Right-click the downloaded `.zip` and extract it.
2. **Install Steam Tools** – Download [Steam Tools](https://www.steamtools.net/) and install.
3. **Drag & Drop Files** – Select all extracted Lua files and drag them onto the Steam Tools icon.
4. **Restart Steam** – Restart Steam fully to apply changes.

⚠️ Always **backup original files** before applying modifications.

---

## ❓ FAQ

**Q: How do I find my Game’s Steam ID?**
👉 Visit the game’s Steam store page – the number in the URL is your Game ID. Or use [steamdb.info](https://steamdb.info).

**Q: Are these files safe?**
👉 Yes. All Lua files are scanned, verified, and widely used by the community.

**Q: Why is LuaGen so fast compared to other tools?**
👉 LuaGen is powered by:

* **Cloudflare CDN** for global caching and instant delivery.
* **Pre-compiled `.zip` archives** (no server-side building).
* **Direct file mapping by Game ID** (no database lookup needed).

**Q: How do you manage 32,000+ files?**
👉 Files are stored as **flat static `.zip` archives**, served via CDN. This avoids complex databases and ensures minimal overhead. Cloudflare handles global caching, making even large collections extremely fast to access.

---

## 📊 Technical Details

* **Frontend:** HTML + CSS
* **Hosting:** Cloudflare Pages (static deployment)
* **File Storage:** CDN-backed file server + GitHub backup mirror
* **Backup:** GitHub ZIP archives (auto fallback if primary fails)

---

## 🔗 Live Demo

👉 [luagen.pages.dev](https://luagen.pages.dev)

## 📧 Support

For missing files, requests, or issues:
**Email:** [pocox5proextrime@gmail.com](mailto:pocox5proextrime@gmail.com)

---

⭐ If you find LuaGen useful, consider giving this repo a **star** on GitHub!
