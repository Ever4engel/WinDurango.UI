# WinDurango.UI
[![Join our Discord](https://img.shields.io/discord/1280176159010848790?color=2c9510&label=WinDurango%20Discord&logo=Discord&logoColor=white)](https://discord.gg/mHN2BgH7MR)
[![View stargazers](https://img.shields.io/github/stars/WinDurango-project/WinDurango.UI)](https://github.com/WinDurango-project/WinDurango.UI/stargazers)   
GUI for WinDurango, which allows you to install the compatibility layer into packages, as well as manage mods and saves. (+ more coming later probs)

> [!IMPORTANT]
> WinDurango.UI's C# codebase is obsolete, and will not be updated.
>
> Instead, it will be rewritten in C++ using QT, and link directly against WinDurango itself for handling settings.
>
> If you wish, you may view the old codebase in the `legacy/winui` branch.

# Roadmap

## Features
 - [ ] Patching
 - [ ] Allow for package removal from UI instead of just completely uninstalling.
 - [ ] Installation options
 - [ ] Save Manager
 - [ ] Mod Manager
 - [ ] Scan for already installed EraOS/XUWP stuff
 - [ ] Allow for any existing installed & patched package to be added to the applist
   - Instead of showing all ERA applications, we will allow the user to select an application to patch, and once patched it will be added into the launcher UI.
 - [ ] Built in updater
 - [ ] Controller support 
 - [ ] Setup program (maybe MSIX?)
 - [ ] Fitting place for extra xbox-specific info
 - [ ] Allow for search
