# On Package Management

The absence of a Windows package manager might have left a void for other solutions like [Chocolatey](https://chocolatey.org/), which I use to some extent (Not all applications are available on Chocolatey).  
<sub>Yes, there is [WinGet](https://github.com/microsoft/winget-cli) now, but it will take some time until a stable and widely adopted version is ready. At the moment it's just a glorified downloader and does neither "package" nor "management". Possibly these design issues can never be fixed...</sub>

Since [this repo](https://github.com/runxel/uses) is also a personal list for me in case I need to re-build my machine in an emergency or migrate to a new machine I include a [`packages.config`](packages.config) here.

### How that was generated
Export the `packages.config` with this command via your terminal:  
```shell
choco export -o c:/temp/packages.config --include-version-numbers
```

This file can then be utilized via  
```shell
choco install packages.config -y
```

<del>
While there is an option inside the Chocolatey _GUI_ the [implementation](https://github.com/chocolatey/choco/pull/1825) of a `choco export` for the CLI is still not available.  
Instead I use a [powershell script](https://github.com/runxel/powershell/blob/master/export-chocolatey-list.ps1) to make the `packages.config` file.
</del>
