# Installing Oh My Posh in PowerShell 7 (WIndows 10)

## Install PowerShell 7 on Windows 10
https://docs.microsoft.com/pt-br/powershell/scripting/install/installing-powershell-core-on-windows?view=powershell-7.1

### How to call powershell on terminal
The installation do not replace the powershel 5.x version. To call the Powershell 7 executable on the terminal we need to look for pwsh.exe and not powershell.exe. Powershell.exe is for the version 5.x of the program that continues in the OS.

## Install Oh My Posh and Posh Git on PowerShell
- [Oh My Posh - PowerShell](https://ohmyposh.dev/docs/pwsh)
- [Tutorial: Configurar o Powerline no terminal do Windows](https://docs.microsoft.com/pt-br/windows/terminal/tutorials/powerline-setup)
- [How to make a pretty prompt in Windows Terminal with Powerline, Nerd Fonts, Cascadia Code, WSL, and oh-my-posh](https://www.hanselman.com/blog/how-to-make-a-pretty-prompt-in-windows-terminal-with-powerline-nerd-fonts-cascadia-code-wsl-and-ohmyposh)
- https://ohmyposh.dev/docs/pwsh
- 

### Fix Font Gliphs
Oh My Posh Gliphs dont work with Cascadia Code PL, the terminal font has to be changed to Nerd Font. I used Meslo, like suggested in Posh -> Fonts Documentation.
We have to set the Meslo Font in every place that the pwsh is called. In my case, I had to config the font on VSCode, Windows Terminal and PowerShell itself.
- [Oh My Posh - Fonts](https://ohmyposh.dev/docs/fonts)
- [Download da fonte Nerd Font](https://www.nerdfonts.com/font-downloads)

