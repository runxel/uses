# On Package Management

The absence of a Windows package manager might has left a void for other solutions like [Chocolatey](https://chocolatey.org/), which I use to some extent.  
<sub>Yes, there is [WinGet](https://github.com/microsoft/winget-cli) now, but it will take some time until a stable and widely adopted version is ready. At the moment it's just an glorified downloader and does neither "package" nor "management".</sub>

Since [this repo](https://github.com/runxel/uses) is also a list for me in case I need to re-build my machine or migrate to a new machine I include a [`packages.config`](packages.config) here.

#### How that was generated
While there is an option inside the Chocolatey _GUI_ the [implementation](https://github.com/chocolatey/choco/pull/1825) of a `choco export` for the CLI is still not available.  
Instead I use a [powershell script](https://github.com/runxel/powershell/blob/master/export-chocolatey-list.ps1) to make the `packages.config` file, which then can be utilized via
```shell
choco install packages.config -y
```
