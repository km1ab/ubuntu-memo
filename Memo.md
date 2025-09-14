# Ubuntu メモ
## Ubuntu 24.04 のapt update でハマったメモ

https://gist.github.com/hakerdefo/8d0cac9fa3aa0a632216742590e3e441
の
Jul 29あたりの以下を作成したら、いけた！！　→コピペ
/etc/apt/sources.list.d/ubuntu.sources

ソースリストが、deb822とかいう形式が変わった？？

https://zenn.dev/mtkn1/articles/ubuntu-noble-repository-source

24.04は、sources.listは卒業（リネーム）
https://www.reddit.com/r/Ubuntu/comments/1cljldb/cant_update_packages_in_ubuntustudio_2404_weird/?tl=ja

## VS Code起動時にパスワードを求められる件
毎回、うんざりしてしまう<br>

解決法はこれ↓<br>
https://obel.hatenablog.jp/entry/20220126/1643137200

## リポジトリ
- 本家
  - https://archive.ubuntu.com/ubuntu/dists/
  - https://security.ubuntu.com/ubuntu/dists/
- ミラー（日本）
  - https://ftp.udx.icscoe.jp/Linux/ubuntu/dists/


本家は、なぜセキュリティとアーカイブの方でリポジトリが別れているのかは不明
