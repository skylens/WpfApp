# Windows Presentation Foundation Demo

Windows Presentation Foundation Demo

### devenv

```cmd
devenv /Clean "Release|Any CPU" WpfApp.sln /Project WpfApp.UI
devenv /Rebuild "Release|Any CPU" WpfApp.sln /Project WpfApp.UI
```

### msbuild

```cmd
msbuild WpfApp.sln /p:Configuration=Release /t:Clean
msbuild WpfApp.sln /p:Configuration=Release /t:Rebuild
```
