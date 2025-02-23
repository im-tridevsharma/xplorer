<div align="center">
<img height=150 src="./icons/icon.svg" />
</div>

<p align="center"><span><b>Xplorer</b>, a customizable, modern and cross-platform file explorer.</span></p>
<h4 align="center"><span><a href="https://xplorer.vercel.app/community/support/">Supports</a></span> • <span><a href="https://github.com/kimlimjustin/xplorer/discussions">Discussion</a></span> • <span><a href="https://xplorer.vercel.app">Documentation</a></span></h4>

<div align="center">

[![LICENSE](https://img.shields.io/github/license/kimlimjustin/xplorer.svg?style=for-the-badge)](https://github.com/kimlimjustin/xplorer/blob/master/LICENSE) [![Download Counts](https://img.shields.io/github/downloads/kimlimjustin/xplorer/total.svg?style=for-the-badge)](https://github.com/kimlimjustin/xplorer/releases) [![Stars Count](https://img.shields.io/github/stars/kimlimjustin/xplorer.svg?style=for-the-badge)](https://github.com/kimlimjustin/xplorer/stargazers) [![Forks Count](https://img.shields.io/github/forks/kimlimjustin/xplorer.svg?style=for-the-badge)](https://github.com/kimlimjustin/xplorer/network/members) [![Watchers Count](https://img.shields.io/github/watchers/kimlimjustin/xplorer.svg?style=for-the-badge)](https://github.com/kimlimjustin/xplorer/watchers) [![Issues Count](https://img.shields.io/github/issues/kimlimjustin/xplorer.svg?style=for-the-badge)](https://github.com/kimlimjustin/xplorer/issues) [![Pull Request Count](https://img.shields.io/github/issues-pr/kimlimjustin/xplorer.svg?style=for-the-badge)](https://github.com/kimlimjustin/xplorer/pulls) [![Follow](https://img.shields.io/github/followers/kimlimjustin.svg?style=for-the-badge&label=Follow&maxAge=2592000)](https://github.com/kimlimjustin) [![Discord Server](https://img.shields.io/discord/893135322093871104?style=for-the-badge)](https://discord.gg/eM2hsDMtjq)

[![Windows Support](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/kimlimjustin/xplorer/releases) [![Ubuntu Support](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)](https://github.com/kimlimjustin/xplorer/releases) [![Arch Linux Support](https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white)](https://github.com/kimlimjustin/xplorer) [![Windows Support](https://img.shields.io/badge/MACOS-adb8c5?style=for-the-badge&logo=macos&logoColor=white)](https://github.com/kimlimjustin/xplorer/releases)

</div>

---

# What is Xplorer?

![Demo](docs/static/img/Xplorer%20win.png)

<details>
<summary>
More Screenshots
</summary>

![Demo](docs/static/img/Xplorer%20linux.png)
![Demo](docs/static/img/Xplorer%20mac.png)

</details>

Xplorer is a file explorer built from ground-up to be fully customizable. And even without customization, it also looks modern!
It is cross-platform, built using Electron Technology that allowed our File Explorer to be run not only in Windows, but also Linux and MacOS alike.
It also allowed file preview directly inside it, not only pictures or documents, but also videos!

To summarize, Xplorer's features contain:

-   Looks modern
-   Easy to use
-   Cross-platform
-   File Preview, even videos!
-   Most importantly, FOSS, Free and Open Source, which mean you can change components inside if you see fit

Xplorer is currently in development. Suggest improvements in Xplorer [Discussions](https://github.com/kimlimjustin/xplorer/discussions/) or [contribute to it](https://xplorer.vercel.app/community/Contributing/)!

## Installation

You can access the insider version [here](https://github.com/kimlimjustin/xplorer/releases). Please note that it is not stable yet. Use it on your own risk.

## Common Problems

**NB: For installation common problems, please visit this page [here](https://xplorer.vercel.app/docs/install/#common-problems)**

<details>
<summary>
Xplorer keep loading and crashes.
</summary>
Try open cmd by typing `Win + R` and type `cmd`.
Enter following command:

```
wmic
```

If the output says the `wmic` is not recognized as internal or internal command, please follow following steps given on [this](https://superuser.com/questions/1178674/wmic-is-not-recognized-as-an-internal-or-external-command-operable-program-or) or [this](https://knowledge.informatica.com/s/article/156865?language=en_US).

Also, please make sure that windows defender isn't blocking Xplorer from accessing your documents.

</details>
<details>
<summary>
Opening folder like <kbd>Documents</kbd>, <kbd>Desktop</kbd>, <kbd>Downloads</kbd> makes Xplorer crash
</summary>

Disable the [`Extract exe file icon and make it as preview`](https://xplorer.vercel.app/docs/guides/setting/#extract-exe-file-icon-and-make-it-a-preview) setting.

Also, please make sure that windows defender isn't blocking Xplorer from accessing your documents.

</details>
<details>
<summary>
Xplorer is unstable after installing it.
</summary>
Simply restart, Xplorer will fix itself, if it doesn't, please address an issue over [here](https://github.com/kimlimjustin/xplorer/issues)

</details>

## Development

For more info, visit [Xplorer's Contributing guide](https://xplorer.vercel.app/community/Contributing)

### Gitpod for Xplorer's development

Gitpod is a Ready-to-Code environment in which you don't need to worry about dependency errors or lagging your computer. Hit the button below and log in to GitHub with your GitHub account. Then, after it loads, you end up with a VS Code-like environment where you can start developing and pushing your changes.

**Very Important Note: Remember to reload the Gitpod website after it loads up since it won't start the servers immediately, but by reloading, you can get it started. If you are developing the app, go to the Remote Explorer on the sidebar and visit port _6080_ which opens the noVNC app server. If you are developing the docs, go to the Remote explorer but instead of port 6080, visit port _3000_. You can edit normally as you do in VS Code, but if you want to use it locally, clik the hamburger menu button and click _Open in VS Code_.**

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#/https://github.com/kimlimjustin/xplorer)

## LICENSE

[Apache-2.0](https://github.com/kimlimjustin/xplorer/blob/master/LICENSE)
