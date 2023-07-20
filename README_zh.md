# Xstop
轻点即可暂停/恢复 x11 窗口，以降低cpu占用，减少发热。受 [xkill](https://man.archlinux.org/man/xkill.1) 和 [xsuspender](https://github.com/kernc/xsuspender) 启发。

## 使用方法
从 AUR 安装：
```bash
paru -S xstop
```
然后在系统设置里添加一个快捷键，命令为 `xstop`

按下快捷键，光标变成十字形，鼠标左键点击任意 x11 窗口，即可暂停该窗口的进程与子进程；再次按下快捷键点击即可恢复。

在暂停期间该窗口无响应，显示画面可能异常，操作会一直堵塞直到恢复。