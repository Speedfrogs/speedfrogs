# windows配置v2rayN从小白到进阶教程
v2rayN适合初次使用v2机场及不喜欢折腾的用户，优点是操作简单、使用稳定，缺点是不太符合精致翻墙男的审美观，长得不太好看。本教程从小白到进阶以及在使用过程中遇到的问题汇总，是win系统v2rayN最全面的使用教程，仅此一篇文章，包罗所有v2rayN的问题，不多啰嗦直接上教程。
* <a href="#mark1">如何测试节点的延迟和带宽</a>
## 软件下载
直接去github下载，开源安全（需要翻墙访问），下载链接：
https://github.com/2dust/v2rayN/releases/latest
点击v2rayN-Core.zip 自动下载
## 软件设置
v2rayN-Core压缩包————解压————找到v2rayN.exe右键发送快捷方式到桌面，下次直接桌面打开————双击v2rayN.exe（如果提示已停止工作，请下载.net4.0以上版本并安装）
登录网站后按下图操作复制订阅链接：
### ![image.png](https://i.loli.net/2020/09/03/ABVu8ciOrwdtbxQ.png)
打开v2rayN软件界面————上部【订阅】————选择【订阅设置】————按下图配置
### ![image.png](https://i.loli.net/2020/09/03/wex2ACiF6agzsMk.png)
上部【订阅】————选择【更新订阅】————关闭MUX如下（否则无法上网）
### ![image.png](https://i.loli.net/2020/09/03/aLGIm5spE9Qwzgc.png)
选择一个节点按回车（前两项是提示，不要选择！）
桌面右下角 v2 图标右键————http 代理————选择全局（全部去国外）或者 pac 代理（只访问封锁网站的时候才去国外）即可科学上网
注：如需只代理 tg 流量，需要在 tg 的代理设置（设置————高级————链接类型）里选择 sock5，ip 端口设置成 127.0.0.1:10808 即可，此时v2rayN即便是关闭http代理模式下tg依然可用。
<a id="mark1"></a>
## 问题汇总
### 如何测试节点的延迟和带宽
#### 测试延迟
按住shift————鼠标多选节点————右键选择【测试服务器真链接延迟】
此延迟为访问谷歌首页真是延迟，1000ms为打开谷歌时间为1秒钟
反复测试，经常变换节点出现time out，说明此时机场节点不稳定，用起来会出现断流现象，会影响心情
![image.png](https://i.loli.net/2020/09/03/6RePr3oq1zWjJVu.png)
#### 测试延迟
方法1：v2rayN测试带宽步骤同上，右键选择【测试服务器速度】；
方法2：https://speedtest.net 或者 https://fast.com 两种测试均可，测试解决于你所购买机场的带宽对应，比如你买的节点是300M带宽，那测试结果不会超过300M；
方法3：StairSpeedTest脚本测速（教程编写中……）
