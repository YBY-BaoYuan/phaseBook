---
description: Laravel最前置的工作就是配置 Mysql 和 Redis，您需要使用本地或者线上连接他们
---

# 前置工作处理

1. 复制 .env 文件 (备份  方便部署线上)   ps: 如果有多个环境可能会有多个env

![.env](.gitbook/assets/修改env文件（连接Mysql、Redis）)

2\. 初次先不做Redis的配置，后续在讲解

3\. 搭建 mytest 命令行调试

<pre class="language-php"><code class="lang-php">php artisan make:command mytest

//$signature    设置命令名称
//$description  添加命令备注
<strong>//当执行  php artisan  时候会展示</strong></code></pre>

![php artisan make:command mytest](<.gitbook/assets/创建 mytest 命令文件>)

![php artisan](<.gitbook/assets/查看artisan列表 php artisan>)

4\. 修改 config/app.php 文件&#x20;

![config/app.php](.gitbook/assets/时区配置修改)
