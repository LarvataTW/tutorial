{{toc}}

h1. Yii

h2. 線上課程

# 基礎 http://www.imooc.com/view/404
# 外掛 http://www.imooc.com/view/491
# 安全 http://www.imooc.com/view/467
# 效能 http://www.imooc.com/view/440

h2. TDD/BDD 注意事項

以下主要參考 https://github.com/yiisoft/yii2-app-basic/blob/master/README.md#testing
* 修改 tests/*.suite.yml
* 將 composer.json 中的 codeception/base 改為 codeception/codeception
* composer update
* selenium server 請參考 https://github.com/yiisoft/yii2-app-basic/blob/master/README.md#testing 說明
* 修改 config
** 設定 test_db.php
** 設定 test.php，修改以下欄位
*** id, components/db, components/request 等，視需求自行注意
* tests/bin/yii migrate
** 使用的 module 有 migration 也要執行。
* tests/bin/yii serve
** 開啟服務以供測試，此時可用瀏覽器在 8080 port 看到畫面
* vendor/bin/codecept run unit,functional -vvv
** -vvv 會輸出詳細資料
