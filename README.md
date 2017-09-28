# Web-Development-Startup

## Enviorment Setup

### Windows
[Chocolatey](https://chocolatey.org/) is strongly recommended for Windows users to setup different kinds of enviorment.

If you run Windows 7 or less, please update your old-fashoined system. Otherwise, 
you can open PowerShell with administrator privilege and input
```
Set-ExecutionPolicy Bypass; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```
Then you can follow the insturctions to complete your installation and reopen the PowerShell.

If some problems occur, see the [offcial installation guide](https://chocolatey.org/install).

Before installing a package, search it on the [chocolatey gallery](https://chocolatey.org/packages).
Then input `choco install -y package_name` to install it.
`-y` is added in order to make the installation process more convenient.

### MacOS
[Homebrew](https://brew.sh/) is strongly recommended for Mac users to setup different kinds of enviorment.

Open the terminal and input
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
HomeBrew will be automatically installed after several minutes.

I think it's not very possible to meet an error, if so, check the website above.

Similar to Windows, HomeBrew packages can be found on [Formulae](http://formulae.brew.sh/).

### Linux
Most of Linux distributions contains a package manager containing most of packages you need.

I think you are able to setup the enviorment without the guide.

