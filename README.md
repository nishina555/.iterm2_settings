## 設定のインポート

### エクスポートされた設定ファイルをgitから取得する

```
$ cd ~
$ git clone https://github.com/nishina555/.iterm2_settings.git
```

### 設定ファイルをiterm2に紐付ける

- Preferences -> General -> Prferences の「Load preferences from a custom folder or URL」にチェック
- URLのパスに先ほど作成した「~/.iterm2_settings」を指定


## 設定のエクスポート

- Preferences -> General -> Prferences の「Save Current Settings to Folder」を選択する

## メモ
ユーザー名が違うとターミナル起動時の `login` コマンドがうまくいかなくなるので、masterのユーザー名(toshiahru.nishina)を置換して利用する

## ローカル設定
ユーザー名を置換した後、ローカルで変更しないといけないもの

### フォントの変更
- preference -> profiles -> Text -> Font
- 14pt MigMix 1M Regular
