# front_dev_env
フロントエンドの開発環境について調査を実施する。

# browserSync
特定のディレクトリを監視して、更新があると同一のURLを開いているブラウザすべてを更新してくれるツール。
firefox, chrome, IEなどブラウザ別様子を見たい時などで便利。

## 参考ページ
[Browsersync - Time-saving synchronised browser testing](https://www.browsersync.io/)
[複数ブラウザ/端末を同期してくれるBrowserSyncが便利 - Qiita](http://qiita.com/yuichiroharai/items/b3daf45ff209f303bf50)

# emmet

# sass

# less

# stylus

# postcss

# gulp
Node.jsのStreamAPIを利用したビルドシステム

## 参考ページ
[Gulp.js入門 - コーディングを10倍速くする環境を作る方法まとめ | 株式会社LIG](http://liginc.co.jp/web/tutorial/117900)

# 環境構築手順
## browserSyncをまず使ってみる
nodeとbrowser-synのインストール
```
brew install node
npm install -g browser-sync
```
インストールの確認
```
browser-sync -V
```
ファイルが更新されたらリロードされるようにする。
```
browser-sync start --server html --files "css/*"
# 複数記載する場合はカンマ区切り
browser-sync start --server html --files "css/*, *"
```


# 用語
Node Packaged Modules(npm)とはNode.js
