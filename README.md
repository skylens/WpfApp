# Windows Presentation Foundation Demo

Windows Presentation Foundation Demo

### devenv

```cmd
# 清理 WpfApp 解决方案下的 WpfApp.UI 项目
devenv /Clean "Release|Any CPU" WpfApp.sln /Project WpfApp.UI
# 重新编译 WpfApp 解决方案下的 WpfApp.UI 项目
devenv /Rebuild "Release|Any CPU" WpfApp.sln /Project WpfApp.UI
```

### msbuild

```cmd
msbuild WpfApp.sln /p:Configuration=Release /t:Clean
msbuild WpfApp.sln /p:Configuration=Release /t:Rebuild
```
