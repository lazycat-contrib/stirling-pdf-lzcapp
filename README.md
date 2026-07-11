# stirling-pdf-lzcapp-

每天 23:00 UTC 检查 `stirlingtools/stirling-pdf` 稳定版本，验证 `docker.1ms.run` 镜像 digest，构建版本化 LPK Release，并自动提交喵喵私有商店。

GitHub Secrets：`APPSTORE_URL`、`APPSTORE_TOKEN`，可选 `APP_ID` 和 `PRIVATE_STORE_GROUP_CODES`。
