Windows 10
前期准备
您需要一台 Windows 10 系统 64 位的电脑

您需要腾出 25~35 分钟的时间

您需要一个喜欢折腾的心

一、安装 Python3
进入 Python 官方下载网址 https://www.python.org/downloads/

点击 Download Python 3.x.x 即可开始下载 Python3 下载完成后点击安装包进入安装程序

先勾选 Add Python 3.x to PATH 然后点击 Install Now 等待一会儿

点击 disable path length limit 然后点击 Close 即可完成安装 Python3 的步骤

二、安装 selenium 的操作
按 Win + r 后输入 cmd.exe 即可打开终端

复制下方代码 粘贴到终端中并按 enter 此步是为了升级 pip 版本

pip install -i https://pypi.tuna.tsinghua.edu.cn/simple pip --user
复制下方代码 粘贴到终端中并按 enter 此步是安装 selenium
pip install -i https://pypi.tuna.tsinghua.edu.cn/simple selenium --user
三、下载 chrome 浏览器
进入 chrome 官方下载网址 https://www.google.com/intl/zh-CN/chrome/

点击下载即可开始下载 下载完成后点击安装包进入安装程序

安装 chrome 并不需要选择或者点击任何地方 很人性化 方便

打开 Google Chrome 浏览器 并在地址栏输入

chrome://version
用文本记录第一行 Google Chrome 后面的版本号即可
四、下载 chromedriver 驱动
进入 chormedriver 官方下载网址 http://chromedriver.storage.googleapis.com/index.html

寻找与 Google Chrome 版本号一样的文件并点击进去

点击 chromedriver_win32.zip 即可开始下载驱动

下载完成后双击 chromedriver_win32.zip 压缩包 将 chromedriver.exe 复制一下

在电脑桌面右键 Google Chrome 选择 打开文件所在位置 并记录地址栏的路径

即 C:\Program Files\Google\Chrome\Application 可能每个人都不尽相同

将 chromedriver.exe 粘贴到这个文件夹内

五、配置 chromedirver 的环境变量
在桌面右键 此电脑 图标

如果找不到 此电脑 图标 参考此教程

点击 属性 后 点击弹窗左侧的 高级系统设置

点击 环境变量 在上方的用户变量中双击 path 或者 PATH

点击右侧的 新建 并将 chrome 浏览器的存放路径粘贴进去 (参考第四步中的第 5 小步)

然后就是点击 确定 确定 和 确定 即可

在终端中输入 (关于什么是终端 参考第二步中的第 1 小步)

chromedriver
控制台输出 Starting ChromeDriver ...... 时则视为配置成功
