<div align="center">

<h1>🧪 Arturo Reach Lab</h1> 

Or... what tools/editors/package managers we do<br>(or could) support for **[Arturo](https://github.com/arturo-lang/arturo)**
</div>

--------------
 
<!--ts-->
   * [Package Managers](#-package-managers)
   * [Editors / Syntax Highlighting](#-editor--syntax-highlighting)
   * [Code Counters](#-code-counters)
<!--te-->

--------------

## 📦 Package Managers & Distribution

| Platform          | Package Manager                                      | Status | Version  | Install Command                                                                                   | Notes                                                       |
|-------------------|------------------------------------------------------|:------:|:--------:|---------------------------------------------------------------------------------------------------|-------------------------------------------------------------|
| **macOS**         | MacPorts                                             | 🔴    |          | —                                                                                                  |                                                             |
| **macOS/Linux**   | [Homebrew](https://formulae.brew.sh/formula/arturo)  | 🟢    | 0.10.0   | `brew install arturo`                                                                              |                                                              |
| **Arch Linux**    | [AUR](https://aur.archlinux.org/packages/arturo)     | 🟢    | 0.10.0   | `yay -S arturo` or `paru -S arturo`                                                                |                                                             |
| **Arch Linux**    | pacman                                               | 🔴    |          | —                                                                                                  |                                                             |
| **Debian/Ubuntu** | APT                                                  | 🔴    |          | —                                                                                                  |                                                             |
| **Fedora/RHEL**   | DNF/YUM                                              | 🔴    |          | —                                                                                                  |                                                             |
| **OpenSUSE**      | Zypper                                               | 🔴    |          | —                                                                                                  |                                                             |
| **Alpine**        | APK                                                  | 🔴    |          | —                                                                                                  |                                                             |
| **Void Linux**    | XBPS                                                 | 🔴    |          | —                                                                                                  |                                                             |
| **NixOS**         | Nix                                                  | 🔴    |          | —                                                                                                  |                                                             |
| **Gentoo**        | Portage                                              | 🔴    |          | —                                                                                                  |                                                             |
| **Linux**         | [Snapcraft](https://snapcraft.io/arturo)             | 🟢    | 0.10.0   | `sudo snap install arturo`                                                                         |                                                             |
| **FreeBSD**       | pkg                                                  | 🔴    |          | —                                                                                                  |                                                             |
| **NetBSD**        | pkgsrc                                               | 🔴    |          | —                                                                                                  |                                                             |
| **OpenBSD**       | pkg_add                                              | 🔴    |          | —                                                                                                  |                                                             |
| **Windows**       | Chocolatey                                           | 🔴    |          | —                                                                                                  |                                                             |
| **Windows**       | [Scoop](https://github.com/arturo-lang/scoop-bucket) | 🟢    | 0.10.0   | `scoop bucket add arturo https://github.com/arturo-lang/scoop-bucket`, then `scoop install arturo` | ⚠️ Ensure you add the bucket first for proper installation.|
| **Windows**       | winget                                               | 🟢    | 0.10.0   | `winget install arturo`                                                                            |                                                             |
| **Docker**        | Docker Hub                                           | 🟢    | 0.10.0   | `docker run -it arturolang/arturo`                                                                 | "Default" version is the MINI build                         |
| **MISE-en-place** | [Mise](https://github.com/arturo-lang/mise-plugin)   | 🟢    | 0.10.0   | `mise plugin install arturo https://github.com/arturo-lang/mise-plugin`, then `mise install arturo`| ⚠️ Ensure you add the plugin first for proper installation.|

### Legend

- 🟢 Available
- 🟠 Not updated
- 🔴 Not Available

## 💻 Editor / Syntax Highlighting

- [x] [**VSCode**](https://marketplace.visualstudio.com/items?itemName=drkameleon.arturo) - Windows / macOS / Linux
- [x] [**SublimeText**](https://packagecontrol.io/packages/Arturo%20Programming%20Language) - Windows / macOS / Linux
- [x] [**Vim/NeoVim**](https://github.com/xigoi/vim-arturo) - Windows / macOS / Linux

## 🌀 Code Counters

- [x] [**cloc**](https://github.com/AlDanial/cloc/releases/tag/v2.02)
- [x] [**scc**](https://github.com/boyter/scc/releases/tag/v3.3.0)
- [x] [**tokei**](https://github.com/XAMPPRocky/tokei/releases/tag/v13.0.0-alpha.2)

---------

> [!NOTE]
> 💡 If you want to add one, just edit this file 😉  
> 🚀 If you want to contribute what's missing, you're more than 100% welcome!
