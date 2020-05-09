# Github page の全体ソース管理用リポジトリ

## 環境構築

はじめにリポジトリをcloneする

```bash
git clone https://github.com/snzy/snzy.github.page.git
```

cloneしたディレクトリでコマンド実行

```bash
bundle exec jekyll serve
```

生成された ```_site```フォルダ内で ```git init``` したあと

```bash
git add --all
git commit -m "change log"
git remote add https://github.com/snzy/snzy.github.io.git
git push origin master
```

## 記事を更新したら

```bash
bundle exec jekyll serve --trace
```
