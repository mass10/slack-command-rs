# 概要

Slack にメッセージを送信する簡単なコマンドです。単一バイナリーファイルと設定ファイルで利用できます。開発環境を構築できない、限られた環境などで利用できます。

# 始め方

### インストール
```bash
cargo install --git https://github.com/mass10/rslack-command --branch main
```

### settings.toml の例
```TOML
[hello]
access_token = "xoxb-xxxxxxxxxxxx-xxxxxxxxxxxxx-xxxxxxxxxxxxxxxxxxxxxxxx"
channel = "notifications"
text = "text message here"
```

### 起動方法
```bash
rslack-command hello
```
