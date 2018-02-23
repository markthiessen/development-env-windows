Step one:

```. { iwr -useb http://boxstarter.org/bootstrapper.ps1 } | iex; get-boxstarter -Force```


Step two:

```Install-BoxstarterPackage -PackageName https://raw.githubusercontent.com/markthiessen/development-env-windows/master/boxstarter -DisableReboots```

