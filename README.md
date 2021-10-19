# asctx

## Overview
This is the context switch helper for `aws sso login`.  
This script assumes that `aws configure sso` has been done.
- https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-sso.html

## Usage
```
$ asctx help
This is the context switch helper for 'aws sso login'

usage:
  asctx        : show context list or use peco to filter context
  asctx config : edit configuration file
  asctx clear  : clear context information

  asctx help   : show this message

$ asctx
# a filter using peco
# open browser
Successfully login to <profile>
```

## Install
```
$ git clone https://github.com/m3y/asctx.git
$ mv asctx /usr/local/bin/asctx
```

## Dependencies
- [awscli v2](https://docs.aws.amazon.com/ja_jp/cli/latest/userguide/install-cliv2-mac.html)
- [peco](https://github.com/peco/peco)


----
Inspired by [kubectx](https://github.com/ahmetb/kubectx)
