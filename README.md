# automatic_backup_boxapi

Periodic automatic backup using Box API with electron

## 参照

https://officeforest.org/wp/2020/09/03/electron%e3%81%a7box-api%e3%82%92%e4%bd%bf%e3%81%a3%e3%81%a6%e5%ae%9a%e6%9c%9f%e8%87%aa%e5%8b%95%e3%83%90%e3%83%83%e3%82%af%e3%82%a2%e3%83%83%e3%83%97/

https://officeforest.org/wp/2020/09/07/electron%E3%81%A7box-api%E3%82%92%E4%BD%BF%E3%81%A3%E3%81%A6%E5%AE%9A%E6%9C%9F%E8%87%AA%E5%8B%95%E3%83%90%E3%83%83%E3%82%AF%E3%82%A2%E3%83%83%E3%83%97-%E5%AE%9F%E8%A3%85%E7%B7%A8/

## npm パッケージについての知識

node cron - 定期的に特定の処理を実行してくれるモジュール(python の timer 的な)

electron-store 　各種設定情報を格納するためのモジュール  
express

box の OAuth2 認証は passport/passportbox を利用する。
