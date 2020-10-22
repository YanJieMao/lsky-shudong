# 兰空树洞

## 更新日志


>#####2019 08-06更新
1.修复了xampp环境下非根目录的网站加载错误
2.修改QQ头像为统一样式头像

> ##### 2018 01-08 更新：
1. 增加后台
2. 系统关键字可自定义
3. 系统参数可自定义
4. 支持悄悄话管理，可在后台删除
5. 优化前端js等

> ###### 说明：
后台账号配置在 config/config.php 文件中，默认账号admin，密码admin<br>
后台地址：http://域名/admin.php<br>
升级指导：已安装1.0版本的小伙伴升级请导入sql目录下的update.sql文件到mysql，然后覆盖1.1版本文件即可。<br>

## 配置要求
- PHP版本 > 5.3
- mysqli支持

## 安装教程：
1. 首先创建一个数据库，下载程序后解压。
2. 把sql目录下的lsky.sql 导入到数据库。
3. 修改config目录下的db.php文件(注意：请勿使用记事本修改)，根据注释修改数据库配置。
4. 访问首页，安装完成！
