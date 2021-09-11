# ディストリビューションを作成

```shell
$ json5 -c min.json5
$ aws cloudfront create-distribution \
  --profile test \
  --distribution-config file://min.json
```

# ディストリビューションの設定情報を取得

```shell
$ export ID=EX8APVOEK2WMZ
$ aws cloudfront get-distribution-config \
  --profile test \
  --id $ID
```
