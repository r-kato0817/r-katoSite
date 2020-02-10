# r-katoSite

## サイト更新方法
```
$ cd ~/GitHub/r-katoSite/
$ hugo server -w  <-- ターミナルの別のウィンドウで
$ open http://localhost:1313/  <-- ローカル環境でサイトを確認
$ hugo  <-- 公開用サイトを作成
$ cd public/
$ git add -A
$ git commit -m "コメント"
# git push  <-- リモートリポジトリ r-kato0817.github.ioに登録されている公開用サイトを更新
$ open https://r-kato0817.github.io  <-- GitHub Pagesを確認
$ cd ..
$ git add -A
$ git commit -m "コメント"
$ git push  <-- リモートリポジトリ r-katoSiteに登録されているHugoのプロジェクトを更新
```
