 # 模拟键盘输入

这是一个使用Python和Tkinter GUI库创建的小工具，它可以模拟键盘输入，将剪贴板的内容输入到当前活动的窗口。

## 功能

- 模拟键盘输入：将剪贴板的内容模拟为键盘输入，可以处理中英文字符。
- 自动检测剪贴板内容：程序会定期检查剪贴板的内容，并在GUI中显示。
- 全局快捷键：使用'ctrl'+'`'快捷键可以立即将剪贴板的内容模拟输入。

## 使用说明

1. 将需要模拟输入的内容复制到剪贴板。
2. 注意如果剪贴板内容开始为中文，输入法需调成中文模式，否则按shift调成英文。
3. 按下'ctrl'+'`'，即可将剪贴板内容模拟输入。

## 依赖

- Python
- Tkinter
- pyautogui
- pynput
- re
- threading
- time

## 作者

@Fnlyu

## 许可

此项目遵循MIT许可。
