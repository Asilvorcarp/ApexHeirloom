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

   1. Before running `Code Cell A` to locate window, make sure your game can be fully displayed when it's in the foreground. And dont move the game window after this.

      > If you choose not to `auto_locate_game`: after running `Code Cell A`, point your mouse cursor at the exact top left corner of the game screen **(title bar not included)** in 3 seconds in order to locate the window.

   2. After running `Code Cell B`, operate the game to capture the buttons.

      This includes: (See the images in the `lib` folder for details) **//TODO**

   3. After running `Code Cell C`, enter the game menu page, then it'll start to repeat automatically (with config of which heirloom do you want).

5. Sit back and relax.

   (when it's done, it'll show a message box)

6. If you want to interrupt it, press `Ctrl + C`. **//TODO**

## Todo

- [x] dont force to be centered, just point at the top left corner

  - [x] use `pywin32` to locate the window

- [x] add Seer

- [x] show process of capturing buttons

- [ ] readme: pages/buttons to capture

- [ ] interrupt

- [ ] show message box

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

   1. 在运行 `Code Cell A` 以定位窗口之前，确保你的游戏在前台时可以完全显示，并且在这之后不要移动游戏窗口。

      > 如果你选择不自动定位窗口(`auto_locate_game`)：在运行 `Code Cell A` 之后，在 3 秒内将鼠标光标指向游戏屏幕的**左上角**（标题栏不包括在内）以定位窗口。

   2. 运行 `Code Cell B` 后，切换游戏界面以捕获按钮。

      这些按钮包括：(详见 `lib` 文件夹下的部分图片) **//TODO**

      它们分布在：(打开这些页面等待提示捕获成功即可)

        1. 游戏外的主菜单界面（选服务器的那个）
        2. 游戏内的主菜单界面（点开始的那个）
        3. 游戏内的ESC界面（按 Esc 打开的那个）
        4. 回到主菜单的确定界面（按 Esc + R 打开的那个）

      在这个过程中，程序会提示剩下要捕获的按钮，全部捕获后会自动结束。

   3. 运行 `Code Cell C` 后，进入游戏菜单页面，然后它将自动开始循环运行（根据您的配置）。

5. 坐下来放松一下。

   （成功后，它将显示消息框）

6. 如果要打断它，请按 `Ctrl + C`。 **//TODO**
