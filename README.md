In an elevated PowerShell far far away... or close, whatever.



### 1. Install boxstarter

```
. { iwr -useb http://boxstarter.org/bootstrapper.ps1 } | iex; get-boxstarter -Force
```


### 2. Set Windows like I wanna


```
Install-BoxstarterPackage -PackageName https://raw.githubusercontent.com/markthiessen/development-env-windows/master/boxstarter-windows -DisableReboots
```

### 3. Install dev tools

```
Install-BoxstarterPackage -PackageName https://raw.githubusercontent.com/markthiessen/development-env-windows/master/boxstarter-tools -DisableReboots
```
