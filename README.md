# 伪 DC 调光
当亮度设置低于某值时，拦截硬件亮度下调，并对应修改极暗模式的压暗强度。  
直接拖动系统亮度条即可自动调节，也不影响截图的亮度。
## 注意
最低屏幕亮度是HAL的亮度值，不一定每台机型都是0\~100%，例如小米12s是0\~50%，你可以调整亮度到不会频闪的最小亮度，然后查看"当前 HAL 亮度"。本人实测小米12s最低亮度为7.99%。
## 已知问题
1. ~屏下环境光传感器的机型，在低亮度下，自动亮度可能乱跳（1.0.1修复）~
2. 会导致其它颜色管理功能（如色温管理、护眼模式等）失效

## 捐赠支持
点个 **Star** 也是对我的支持。
如果这个项目对你帮助很大，可以考虑给我送杯奶茶。

<img align="center" alt="donate_alipay" width = "250" src="https://github.com/Xposed-Modules-Repo/com.ztc1997.fakedcbacklight/raw/main/img/donate_alipay.jpg"/>
<img align="center" alt="donate_wechat" width = "250" src="https://github.com/Xposed-Modules-Repo/com.ztc1997.fakedcbacklight/raw/main/img/donate_wechat.jpg"/>
