# Local Development

You need to have `Jekyll` installed.

You should have `Ruby` and `RubyGems` installed in your system. Guides to setup [Jekyll Installation](https://jekyllrb.com/docs/installation/)

## Permission Error on Bundel Install

Ruby may be already installed in your system and it may be in root. You may not want to `sudo` install packages. There is something called [rvm](https://rvm.io/)

```
rvm list known
rvm install 3.3.3

# you may need to run
source ~/.bash_profile

rvm --default use 3.3.3
```