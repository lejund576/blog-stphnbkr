+++
title = "EVE-NG"
date = "2022-10-31"
author = "Steve"
cover = ""
description = ""
tags = ["EVE-NG", ]
toc = true
draft = false
+++

Every so often, I'll encounter an issue with EVE-NG where I have to start searching online for a fix. 

This post will store any issues I encounter while labbing and document the fixes in case I need to refer to them later. 

_________________


## Web Console

Occassionlly when the VM is powered on I can't browse to the web console.

Access the EVE-NG console or via SSH, login (root/eve) and try the following:

> Fix permissions:
> ```"/opt/unetlab/wrappers/unl_wrapper -a fixpermissions"```
>
> Check allocated harddrive space:
> ```df -h```
>
> Restore SQL Database
> ```"unl_wrapper -a restoredb"```

&nbsp;