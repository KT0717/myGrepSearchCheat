## 特定の文字列を含むファイルを検索する grep コマンド

https://www.t3a.jp/blog/infrastructure/grep-search-file/

```
find (検索対象のフォルダ) -type f | xargs grep (検索する文字列)
```

```
find ./ -type f | xargs grep test
```
