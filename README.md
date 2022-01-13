Wordpress + SAML連携
====================


環境
----------

* wordpress, latest


機能
----------

|   機能    |          URL           |
| --------- | ---------------------- |
| Wordpress | http://localhost/      |
| DBツール  | http://localhost:8080/ |


使い方
----------

### 通常利用時

```bash
# コンテナ起動
docker-compose up -d

# コンテナ停止
docker-compose down

# コンテナ停止(ボリュームも削除)
docker-compose down -v
```
