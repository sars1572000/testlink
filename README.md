# Testlink

### 說明：

SERVER IP ：`192.168.128.190`

WEB URL：`http://testlink.winhua.local `or` http://192.168.128.190:10280`

DB 連線資訊：`192.168.128.190:45036`

WEB跟DB帳密跟之前一樣

### Detail：

Docker Mount到VM 檔案路徑：

testlink DATA path：/data/devops/testlink_data/

db DATA path：/data/devops/mariadb_data/


### 原docker images來源

bitnami/bitnami-docker-testlink:1.9.16

bitnami/mariadb:latest

### REF

[bitnami github](https://github.com/bitnami/bitnami-docker-testlink#how-to-use-this-image)

[bitnami dockerhub](https://hub.docker.com/r/bitnami/testlink/~/dockerfile/)

### PS.

folder `zh_TW` 及 `const.inc.php` 為了繁體語系包(不是必要)
