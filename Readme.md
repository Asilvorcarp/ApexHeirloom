# GetApexHeirloom

Get the Apex Heirlooms by glitching the game.  

## How to use

0. Install packages.

    ```bash
    pip install -r requirements.txt
    ```

1. Set your game language to Simplified Chinese (for image recognition).

2. Set your game display mode and resolution to Windowed and 1280x720.

3. Modify the `configs` code cell to your needs.

4. Run **all** the code cells in order.

   1. After running `Code Cell A`, point your mouse cursor at the exact top left corner of the game screen **(title bar not included)** in 3 seconds in order to locate the window.

   2. After running `Code Cell B`, operate the game to capture the buttons.

      This includes: **//TODO**

   3. After running `Code Cell C`, enter the game menu page, then it'll start to repeat automatically (with config of which heirloom do you want).

5. Sit back and relax.

   (when it's done, it'll show a message box)

6. If you want to interrupt it, press `Ctrl + C`. //TODO

## Todo

- [x] dont force to be centered, just point at the top left corner

  - [ ] use `pywin32` to locate the window

- [ ] show message box

- [ ] readme: pages/buttons to capture

- [ ] add Seer

- [ ] show process of capturing buttons

# 中文版

卡 Apex 传家宝。

## 如何使用

0. 安装依赖。

    ```bash
    pip install -r requirements.txt
    ```

1. 将游戏语言设置为简体中文（用于图像识别）。

2. 将游戏显示模式和分辨率设置为窗口模式和 1280x720。

3. 修改 `configs` 这个代码单元格中的配置（根据你想要的传家宝和顺序）。

4. 依次运行**所有**代码单元格。

   1. 运行 `Code Cell A` 后，在 3 秒内将鼠标光标指在 **游戏画面（不包括标题栏）** 的精确左上角，从而完成定位。

   2. 运行 `Code Cell B` 后，切换游戏界面以捕获按钮。

      包括：**//TODO**

   3. 运行 `Code Cell C` 后，进入游戏菜单页面，然后它将自动开始循环运行（根据您的配置）。

5. 坐下来放松一下。

   （完成后，它将显示消息框）

6. 如果要打断它，请按 `Ctrl + C`。 //TODO
