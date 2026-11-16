<p align="center">
  <img src="https://raw.githubusercontent.com/SnowlineOS/.github/refs/heads/main/snowline-icon.svg" alt="SnowlineOS" width="120" height="120">
</p>

<h1 align="center">SnowlineOS</h1>

<p align="center">
  <strong>A calm, signed Linux. Updated from GitHub, on your terms.</strong>
</p>

<p align="center">
  <a href="https://github.com/SnowlineOS/SnowlineOS">Download</a> ·
  <a href="https://github.com/SnowlineOS/SnowlineUI">Design language</a> ·
  <a href="https://github.com/SnowlineOS/Updates">Updates</a>
</p>

---

> [!NOTE]
> SnowlineOS is in early development. There is no stable release yet. Follow the repositories below to see it take shape.

## What is SnowlineOS?

SnowlineOS is an open-source Linux distribution built around three ideas: a core that can't break, apps that can't harm the system, and one consistent design across everything you see.

- **Immutable core.** The system is a single read-only image. An update replaces it as a whole, and if a start ever fails, SnowlineOS returns to the last working version by itself.
- **Signed, from GitHub.** Every system image is built in the open, signed and published here. Nothing reaches a device that wasn't released in these repositories.
- **Sandboxed apps.** Apps run in their own sandbox and ask before they touch your files, camera or screen. They can never change the system.
- **One design language.** Settings, Files, Calculator and the other system apps are built for SnowlineOS and share SnowlineUI, so the whole system looks and feels like one piece.
- **Ready to be managed.** Organizations can lock settings, set a wallpaper, choose an update channel and approve apps with simple policy files.

## Repositories

| Repository | What's inside |
| --- | --- |
| [**SnowlineOS**](https://github.com/SnowlineOS/SnowlineOS) | The operating system and the installer ISO. Start here to download. |
| [**Updates**](https://github.com/SnowlineOS/Updates) | Update channels and signed system images. Every release is approved here. |
| [**SnowlineUI**](https://github.com/SnowlineOS/SnowlineUI) | The design language: colors, type, icons, components and the reasons behind them. |

Every SnowlineOS app lives in its own repository. More apps such as Settings, Files and Store will follow.

## How updates work

1. Changes land as pull requests and are built and tested automatically.
2. New builds go to the **testing** channel first.
3. A release tag moves a tested build to **stable**.
4. Your device downloads only what changed, checks the signature and switches over on the next restart.

## Editions

**SnowlineOS** is free and open source. Pro and Business editions with long-term support, central management and additional apps are planned on top of the same open core.

## Get involved

- Found a bug or have an idea? Open an issue in the repository it belongs to.
- Want to design with us? Start with [SnowlineUI](https://github.com/SnowlineOS/SnowlineUI).
- Each repository states its own license.

<p align="center"><sub>Built in Austria · Open source on GitHub</sub></p>
