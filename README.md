# dhoco-install-packages
A list of programs I install via [Chocolatey](https://chocolatey.org/packages)

## Install [Chocolatey](https://chocolatey.org/install)

```
Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```

## Install packages via an Administrator privileged console/shell
### My Essentials
```
choco install nodejs.install git cmder jdk8 maven docker-toolbox visualstudiocode intellijidea-ultimate putty virtualbox winscp windirstat yarn filezilla gradle keepass winrar python3 python2 -y
```

### Python
```
choco install python3 python2 -y
```

### Java dev
```
choco install git jdk8 maven intellijidea-ultimate gradle -y
```

### Web dev
```
choco install git yarn visualstudiocode nodejs.install -y
```

### Useful
```
choco install windirstat yarn filezilla winscp -y
```
