---
title: Setup development environment for Mac
date: 2022-12-27 10:51:59
tags:
- Programming
cover: https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fapi.cocoachina.com%2Fuploads%2Fimage%2F20200302%2F1583116203870375.jpg&refer=http%3A%2F%2Fapi.cocoachina.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=jpeg?sec=1640425793&t=621d7a5ff58c96583b4a142b7c0aa219
---
### Homebrew
``` bash
https://gitee.com/cunkai/HomebrewCN?_from=gitee_search

/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/Homebrew.sh)"
```

### rbenv/ruby
``` bash
brew install rbenv ruby-build
# run this and follow the printed instructions:
rbenv init

# list latest stable versions:
rbenv install -l

# list all local versions:
rbenv install -L

# install a Ruby version:
rbenv install 3.2.0

rbenv global 3.2.0   # set the default Ruby version for this machine
# or:
rbenv local 3.2.0    # set the Ruby version for this directory
```

### gem
``` bash
查看源
gem sources -l
更换源
gem sources --remove https://rubygems.org/
gem sources --add https://gems.ruby-china.com/
```
### cocoapods
``` bash
gem install cocoapods
```
