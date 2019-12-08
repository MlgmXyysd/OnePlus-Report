### 日志抓取教程：

1. 开启时间秒数显示

- 1) 进入【设置--显示--状态栏】

![img1](images/1.png)

![img2](images/2.png)

- 2) 点击【时间】

![img3](images/3.png)

- 3) 选择【显示小时、分钟和秒】

![img4](images/4.png)

2. 打开工程模式日志界面

- 方法一（推荐）：

- 1) 下载OnePlus LogKit（下载地址：[GitHub](https://github.com/MlgmXyysd/OnePlus-Report/releases/download/1.0/OnePlus.LogKit_1.0.apk) [百度网盘](https://pan.baidu.com/s/11WAgYYlEn5AfIstSmoCUDw) [酷安](https://coolapk.com/apk/org.meowcat.oneplus.logkit)）[作者：MlgmXyysd，非一加官方应用]

- 2) 安装后直接打开

![img5](images/5.png)

- 方法二：

- 1) 在手机拨号中输入【*#800#】

![img6](images/6.png)

- 2) 如出现提示请点击【进入】

![img7](images/7.png)

- 3) 选择oneplus logkit

![img8](images/8.png)

3. 打开保存日志选项

- 1) 选中【将日志保存至sdcard】

![img9](images/9.png)

- 2) 选中【保存log】

![img10](images/10.png)

- 3) 如出现提示请点击【取消】

![img11](images/11.png)

4. 问题复现（比如：王者卡死）

- 过程中截图或录屏（重要！记录时间点，便于分析）

![img12](images/12.png)

5. 抓取bugreport信息

- 1) 回到【工程模式日志】界面（参考步骤2）

- 2) 点击【其他log日志】

![img13](images/13.png)

- 3) 点击【抓取bugreport信息】（这一步时间较长请耐心等待，等手机振动/有Toast提示/按钮亮起后可进行下一步操作）

![img14](images/14.png)

- 4) 取消选中【保存log】

![img15](images/15.png)

6. 打包分享日志

- 方法一：

- 1) 点击【打包日志并分享】

![img16](images/16.png)

- 2) 点击【分享】（这一步时间较长请耐心等待）

![img17](images/17.png)

- 3) 等弹出分享对话框时，通过【[Bug反馈规则](Bug-report.md)】里的方法将日志发送给我

- 方法二：

- 1) 文件管理打开sd卡根目录下的【oem_log】文件夹

![img17](images/18.png)

- 2) 找到【_current】后缀的文件夹，长按选中

![img18](images/19.png)

- 3) 点击右上角【更多选项】（右上角三个点）

![img19](images/20.png)

- 4) 点击【压缩】

![img20](images/21.png)

- 5) 将压缩后的文件通过【[Bug反馈规则](Bug-report.md)】里的方法发送给我（文件名和文件夹的名字一样，后缀为zip）
