# DashFolioSync

Windows sync agent for [DashFolio](https://www.dashfolio.ai). It sends your OrderClerk trades and orders to your DashFolio account and keeps your RealTest NLV files up to date.

## Download

**[⬇️ Download DashFolioSyncSetup.exe](https://github.com/dashfoliosync/DashFolioSync-releases/releases/latest/download/DashFolioSyncSetup.exe)**

Run `DashFolioSyncSetup.exe`. The installer:

- installs the Microsoft .NET 8 Desktop Runtime if it is missing (signed by Microsoft);
- installs DashFolioSync, or updates an existing installation — your settings are kept.

When setup asks for it, enter your plugin token. To create one, sign in to [dashfolio.ai](https://www.dashfolio.ai) and go to **Plugins → OrderClerk → Settings → Plugin Tokens** in the menu.

## Updates

DashFolioSync checks for new versions on its own. When one is available, you get a notification and a blue dot on the DashFolioSync icon; open the window and click **Update now** — the update downloads, is verified, and installs by itself. You can also click **Check for updates** in the DashFolioSync menu (notification area, next to the clock).

Versions older than 1.5.50 don't update by themselves: download the installer again with the link above.

## Requirements

- Windows 10 or 11 (64-bit)
- An internet connection
- A DashFolio plan that includes DashFolio Sync

## Releases

All versions and their release notes are listed under [Releases](https://github.com/dashfoliosync/DashFolioSync-releases/releases).
The "Source code" archives that GitHub attaches to every release only contain this page — you only need `DashFolioSyncSetup.exe`.
