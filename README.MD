# CHASC Launcher

A free, non-commercial launcher for **Minecraft: Java Edition** with a fast, animated UI, in-game HUD client mod and screenshot manager. *(Türkçe özet aşağıda.)*

> Not affiliated with Mojang Studios or Microsoft. "Minecraft" is a trademark of Mojang Studios.

## Features
- Sign in with your own **Microsoft account** (system browser; the launcher never sees your password)
- Game profiles (version, memory, loader), live server list, screenshots gallery with quick-access drawer
- Optional in-game **CHASC Client** HUD mod for 1.8.9 (FPS, CPS, keystrokes, armor/potion status, zoom, profiles)
- Themes, Discord Rich Presence (local IPC only), no ads

## Privacy & security
- **No backend server.** The launcher talks only to Microsoft / Xbox Live / Mojang services (sign-in, profile, skins, game files) and to the download hosts of the game and its loader.
- **No telemetry, no analytics, no ads.**
- Passwords are never handled by the launcher: sign-in happens on Microsoft's own pages.
- The refresh token is stored **encrypted** with the operating system's user-bound encryption (Windows DPAPI); access tokens are kept in memory only and never written to logs.
- Uses only these Minecraft services endpoints: `POST /authentication/login_with_xbox` and `GET /minecraft/profile`.
- You can remove your account at any time; stored tokens are deleted.

## Status
Under active development (preview). Contact: <your e-mail>.

---

## Türkçe özet
CHASC Launcher; hızlı, animasyonlu arayüzü, oyun içi HUD modu ve ekran görüntüsü yöneticisi olan ücretsiz bir Minecraft: Java Edition başlatıcısıdır. Microsoft hesabınla giriş yaparsın (şifreni launcher görmez), sunucumuz yoktur, veri toplamaz ve reklam göstermez. Token'lar işletim sistemi şifrelemesiyle saklanır.
