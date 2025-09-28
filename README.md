# neovide-neovim

# Windows setup notes

``` sh
winget install --id Microsoft.Powershell --source winget
winget install BurntSushi.ripgrep.MSVC
winget install sharkdp.fd
winget install fzf
winget install ajeetdsouza.zoxide
Set-Content -Path "C:\Users\*USER*\Documents\PowerShell\Microsoft.PowerShell_profile.ps1" -Value "Invoke-Expression (& { (zoxide init powershell | Out-String)})"
winget install Neovim.Neovim
winget install --id Git.Git -e --source winget
winget install zig.zig

z AppData\Local
mkdir nvim
git clone https://github.com/ensolation/neovide-neovim.git .\nvim
```

<div align="center">
    <summary><h1 align="center"></h1></summary>
    <img src="homepage.png" width="90%"/>
</div>

<div align="center">
    <summary><h1 align="center"></h1></summary>
    <img src="config.png" width="90%"/>
</div>
