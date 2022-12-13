[root@oel7-9 maing]# go get github.com/chetanshivaji/g@c579f6a
go: downloading github.com/chetanshivaji/g v0.0.0-20221213161216-c579f6a2e192
go: downloading github.com/chetanshivaji/m v0.1.2-0.20221213160354-a36ba18e5fe0
go: added github.com/chetanshivaji/g v0.0.0-20221213161216-c579f6a2e192
go: added github.com/chetanshivaji/m v0.1.2-0.20221213160354-a36ba18e5fe0
go: added github.com/chetanshivaji/n v0.0.1
[root@oel7-9 maing]# go run main.go
in main
hello post 0.1.1in FUn G
in fun n
in fun md sub of M
[root@oel7-9 maing]# git add .
[root@oel7-9 maing]# git commit -am "tried g"
[master 3559d6c] tried g
 2 files changed, 6 insertions(+), 2 deletions(-)
[root@oel7-9 maing]# git push 
Counting objects: 7, done.
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 615 bytes | 0 bytes/s, done.
Total 4 (delta 2), reused 0 (delta 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/chetanshivaji/maing.git
   63ba8ec..3559d6c  master -> master
[root@oel7-9 maing]# go get github.com/chetanshivaji/m@a36ba18
go: added github.com/chetanshivaji/m v0.1.2-0.20221213160354-a36ba18e5fe0
go: added github.com/chetanshivaji/n v0.0.1
[root@oel7-9 maing]# go run main.g
no required module provides package main.g; to add it:
        go get main.g
[root@oel7-9 maing]# go run main.go
in main
hello post 0.1.1 in M FUN
in fun n
in fun md sub of M
[root@oel7-9 maing]# git add README.txt
fatal: pathspec 'README.txt' did not match any files
[root@oel7-9 maing]# ls
go.mod  go.sum  main.go
[root@oel7-9 maing]# vi README.txt
[root@oel7-9 maing]# 