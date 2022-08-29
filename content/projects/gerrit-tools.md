---
title: "Gerrit Tools"
hideMeta: true
---
[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/thomasfike.gerrit-tools?style=for-the-badge&logo=visualstudiocode)
![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/thomasfike.gerrit-tools?style=for-the-badge&logo=visualstudiocode)](https://marketplace.visualstudio.com/items?itemName=ThomasFike.gerrit-tools)
[![GitHub issues](https://img.shields.io/github/issues/ThomasFike/gerrit-tools?style=for-the-badge&logo=github)](https://github.com/ThomasFike/gerrit-tools/issues)
Gerrit Tools is a [Visual Studio Code](https://code.visualstudio.com/) extension that I made to make using the [Gerrit Code Review](https://www.gerritcodereview.com/) tool in VS Code. One of the hardest part about using Gerrit with VS Code is that there is no built in mechanism for pushing in the way you have to push to gerrit. This is because instead of just being able to do `git push origin main` you have to do `git push origin HEAD:refs/for/main`. While this is annoying, having to do this over and over again is really annoying. Well to make this easier I wrote this extension to push to gerrit all within the VS Code GUI without having to use the command line.
## Using Gerrit to develop
While the code is mainly hosted on github it is actually worked with using [GerritHub](https://gerrithub.io). GerritHub is a really cool tool from GerritForge that allows you to use gerrit and github interchangeably. This is awesome becuase it allows you to use Gerrit while also using Github. Gerrit is also typically hosted locally and so this allows people to use gerrit that may have never had to chance before. You can find the project on GerritHub [HERE](https://gerrithub.io/q/project:ThomasFike/gerrit-tools).
## Install
### Option 1:
Install from visual studio code market: https://marketplace.visualstudio.com/items?itemName=ThomasFike.gerrit-tools
### Option 2:
Install via the code cli. Run the following command
```bash
code --install-extension thomasfike.gerrit-tools
```