# ansible_epgstation
AnsibleでEPGStationを導入するやつ


# デプロイ方法

## 事前準備

`.ssh/config`に追加する

```
Host epgstation
  HostName ホスト名
  User ユーザー名
  Port ポート番号
  IdentityFile 鍵
```

## 実行

```
ansible-playbook -i production site.yml
```

