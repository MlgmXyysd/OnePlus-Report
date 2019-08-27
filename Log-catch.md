### 日志抓取教程：

1. 下载OnePlus LogKit应用，安装后直接打开

- 下载地址：
[GitHub](https://github.com/MlgmXyysd/OnePlus-Report/releases/download/1.0/OnePlus.LogKit_1.0.apk)
[百度网盘](https://pan.baidu.com/s/11WAgYYlEn5AfIstSmoCUDw)

- 或在手机拨号中输入*#800#，点击进入，选择oneplus logkit

![第1步](images/1.png "第1步")

2. 进入后先勾选第二个，再保存log（重点）

![第2步](images/2.png "第2步")

![第3步](images/3.png "第3步")

- 保存后出现这个，选取消

3. 问题复现（比如：王者卡死），过程中截图或录屏（记录时间点，便于分析）

4. 回到oneplus logkit界面--其他log日志--抓取bugreport信息（时间较长需要等待）

![第4步](images/4.png "第4步")

![第5步](images/5.png "第5步")

5.	取消勾选“保存log”

6.	日志在sd卡下的oem_log文件夹内，压缩打包即可
