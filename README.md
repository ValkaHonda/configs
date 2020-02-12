#### Git

# This is Git's per-user configuration file.

[user]
name = Valentin Aleksandrov
email = valentin.aleksandrov@tick42.com

# Please adapt and uncomment the following lines:

#name = Valentin Aleksandrov
#email = valentin.aleksandrov@tick42.com
[push]
default = tracking
[alias]
c = commit -m
co = checkout
a = add
d = diff --word-diff=color
sh = show --word-diff=color
dic = diff --cached
pl = pull --rebase
ps = push
st = status
out = log origin..HEAD
qpl = log --pretty=\"%Cblue%h%Creset %Cgreen[%cr]%Creset %s\" origin/develop..origin/master
l = log --all --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr)%Creset %Cblue%an%Creset' --abbrev-commit --date=relative
ci = commit
ca = commit --amend
[core]
editor = vim
#pager = C:/cygwin64/bin/less.exe
