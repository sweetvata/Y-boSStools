# boSS Tools

WPF-лаунчер для скриншера. Скачивает форензик-тулзы, запускает PowerShell-скрипты, открывает ссылки — всё в одном окне

## Запуск

```
powershell.exe -NoProfile -STA -ExecutionPolicy Bypass -Command "iex (irm 'https://raw.githubusercontent.com/sweetvata/Y-boSStools/main/installer.ps1')"

```

Требует прав администратора — запросит UAC автоматически

## Что внутри

| Категория | Что |
|---|---|
| **Y Tools** | Свои тулзы — Y-Check, Y-AmCache, Y-Jdamp, Y-Alts |
| **OrbDiff** | Prefetch View++, BAM Reveal, InjGen, JAR Parser и др. |
| **Spokwn** | BAM Parser, Journal Trace, Activities Cache и др. |
| **Tonynoh** | Meow Resolver, Doomsday Fucker, Client Fucker и др. |
| **RedLotus** | Mod Analyzer, Task Sentinel, Alt Checker |
| **DetectAC** | Amcache++, Autoruns++, Journal Trace++, String Explorer++ и др. |
| **Vortex** | Prefetch, MFT Plus, AmCache, FAT, Viewer от dot-sys |
| **Scripts** | PS-скрипты — PC-Check, Services, Macro Scanner и др. |
| **NirSoft** | Full Event Log View, USB Deview, ShellBags View и др. |
| **EricZimmerman** | AmcacheParser, PECmd, MFTECmd, RegistryExplorer и др. |
| **Others** | Jarabel, Luyten, HxD, Hayabusa, System Informer и др. |
| **Dependencies** | .NET 8/9/10, Visual C++ Redistributable |


## Где скачанные файлы

Всё падает на рабочий стол в папку `papa`, по подпапкам категорий:

## Требования

- Windows 10 / 11
- PowerShell 5.1+
- .NET Framework 4.5+ (для WPF, уже есть в Windows)
- Права администратора
