---
layout: default
title: "Linux Github Saga"
---

*Editor's Note: This is an unformatted dialogue I had with myself while trying to push using Obsidian Git through the school internet, via SSH. I have no clue how it works, for some reason I needed to use the Mac config file? Who knows how that works.*

poggg???
(test 2, after restart)

test 3, using school internet (i got beaned by printer notification)

benaning

help it doesnt work

looks like my spec stuff didnt transfer ababouey 

test1(pure setup): tick
test2(after restart): tick
test3(using https config file): fail
test4(config + remote repo change to https): fail!
test5(https but no config): fail
test6(mac version of config): tick
test6(give config perms): tick?
test7(add mac version): tick?
test8(restart,no command): tick
**current conclusion: the following works to push at home:**
- base ssh
- config of following:
```
Host github.com

Hostname ssh.github.com

Port 443

User git

AddKeysToAgent yes

IdentityFile ~/.ssh/id_ed25519
```
- url: ssh

(we have reached day 4 of the struggle with linux, i may or may not have "accidentally" "deleted" a "critical package" from linux and had to reinstall)

## the biggest test of them all: school internet


test9(at school): tick
test10(second push): tick
test11(after restart): tick
test11(accept win push): tick
