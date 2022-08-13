# isucon_11
isucon_11

- isucon/webapp のみを登録する
- isucon/webapp/rustは除く、大きい&不要と思われるため

```
/home/isucon$ du -sh isucon
5.7G                         // 全体はサイズでかい
/home/isucon$ du -sh webapp/
1.2G	webapp                 // webapp のみを登録する
```

```
/home/isucon/webapp$ du -sh *
8.0K    NoImage.jpg
4.0K    ec256-public.pem
632K    frontend
9.5M    go
104M    nodejs
56K     perl
34M     php
816K    public
36K     python
18M     ruby
1.1G    rust                 // rustは除く、サイズでかい&不要と思われるため
916K    sql
```


