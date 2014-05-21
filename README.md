# 在 windows 中安装 node.js

1. 打开cmd
2. 执行

```
@powershell -NoProfile -ExecutionPolicy unrestricted -Command "iex ((new-object net.webclient).DownloadString('https://chocolatey.org/install.ps1'))" && SET PATH=%PATH%;%systemdrive%\chocolatey\bin
```

3. 执行

```
cinst nodejs
```
