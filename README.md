# ChenPay
ChenPay([https://github.com/ChenSee/ChenPay](https://github.com/ChenSee/ChenPay))实际应用，基于Workerman，支持Whmcs对接

该程序需要需要php-posix和php-curl扩展!请务必安装!

git clone后执行composer install 并按照config.php中的说明配置好即可,使用'php /路径/start.php -d'进行运行

如果您目标机器没有composer,也可以使用releases里提供的zip包解压缩后配置config.php并使用'php /路径/start.php -d'进行运行

Whmcs支付插件位于WhmcsPay文件夹内,上传到modules/gateways并在Whmcs后台启用配置即可

Alipay Cookies获取可参照ChenPay([https://github.com/ChenSee/ChenPay](https://github.com/ChenSee/ChenPay))文档
