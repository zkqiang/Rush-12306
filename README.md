# 12306 抢票助手
基于 Selenium 运行，通过模拟点击加快 12306 查票请求，结合网站自带的自动提交功能进行下单，并支持邮件通知支付；  
全程在 12306 网站模拟操作，降低 12306 频繁更新导致 Cookie、API 变化的影响。

## 运行环境
* Python 3 以上
* Selenium + WebDriver  
建议 Chrome 或 Firefox，不要使用无界面浏览器

## 使用说明
* 直接`$python3 rush_12306.py`即可，根据`print`信息进行操作，先手动登录账号和选择查票条件，按回车开始抢票；
* 默认使用`Chrome`浏览器驱动，并关闭邮件通知，如需修改可编辑`rush_12306.py`中的全局变量。