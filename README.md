# isucon_11
isucon_11

- isucon/webapp のみをgithu登録する
- isucon/webapp/rustは除く、大きい&不要と思われるため

以下のようなことをしています

```
$ cd /home                                       # /home へ移動
$ mv isucon isucon.org                           # isuconディレクトリを別名で保存
$ git clone https://github.com/seigot/isucon_11  # isucon_11 を clone
$ ln -s isucon_11 isucon                         # isucon --> isucon_11 へシンボリックリンクを貼る
$ ls -l isucon
lrwxrwxrwx 1 root root 9 Aug 13 20:49 isucon -> isucon_11
```

サイズは以下の通り

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


