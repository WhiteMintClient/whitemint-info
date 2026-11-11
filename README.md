# WhiteMint Client

A lightweight Minecraft: Java Edition client, made of a custom launcher and client-side mods, focused on PvP quality of life and low resource usage. Currently in development.

## Components
- **Launcher** – a small desktop launcher (built with Tauri, not Electron) designed to use very little CPU, memory, GPU and disk. Tabs: Play, Mods, Settings, Logs.
- **Mods** – client-side mods with clean, readable in-game features and sensible default settings.
- **Resource pack** – "WhiteMint PvP", a PvP and UI theme pack with a mint color scheme, published on Modrinth.

## Planned
- Skin and cape support
- Companion mobile app for browsing Modrinth mods and sending them to the PC launcher

## Microsoft / Minecraft sign-in
WhiteMint Client signs players in with their own Microsoft account using the standard device-code / OAuth flow (XboxLive.signin scope), then Xbox Live, XSTS and the Minecraft services login. It uses api.minecraftservices.com only to log the player in, check game ownership and read their own profile. Tokens are used only on the player's own device. They are never sent to a server run by this project or to any third party. The project does not collect passwords and does not sell or trade accounts.

## Not included
No cheats or features that give unfair advantages on multiplayer servers. WhiteMint Client is not affiliated with Mojang or Microsoft.

## Contact
@whitemintclient@gmail.com
