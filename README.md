# Win11TaskbarIconSize
Windows 11 task bar icon size.

`win11_taskbar_icon_size.reg` 内容如下:

```plaintext
Windows Registry Editor Version 5.00

[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced]
"TaskbarSi"=dword:00000000
```

### 使用方法

1.  双击 `win11_taskbar_icon_size.reg` 文件，确认提示以导入注册表。
4. 完成后，重启explorer或注销或重新启动电脑再登录，即可看到任务栏图标变小。

如果你想恢复为中等图标，将最后一行(第4行)的 `dword:00000000` 改为 `dword:00000001`。

