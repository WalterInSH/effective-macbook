# effective-macbook
A list of effective ways to use a Macbook

## Manage your apps

* [Homebrew](https://brew.sh/)
* [Homebrew cask](https://caskroom.github.io/)

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew tap caskroom/cask
```

## Use a more friendly command line

### [Iterm2](https://www.iterm2.com/downloads.html)
### [Iterm2 themes](https://github.com/mbadolato/iTerm2-Color-Schemes)

## Install neccessary command line tools

* [GNU coreutils](https://github.com/coreutils/coreutils)
* [git](https://git-scm.com)
* [openssl](https://openssl.org/)
* [tree](http://mama.indstate.edu/users/ice/tree/)
* [autojump](https://github.com/wting/autojump)
* [dos2unix](https://waterlan.home.xs4all.nl/dos2unix.html)
* [parquet-tools](https://parquet.apache.org/)
* [libcouchbase](https://developer.couchbase.com/documentation/server/4.5/sdk/c/start-using-sdk.html)
* [proxychains-ng](https://sourceforge.net/projects/proxychains-ng/)
* [jenv](http://www.jenv.be)
* [httpie](https://httpie.org/)
* [unrar](https://www.rarlab.com/)

```
brew install coreutils git openssl tree autojump dos2unix parquet-tools libcouchbase proxychains-ng jenv httpie unrar
```

## Use aliases when you can

```
alias ..='cd ..'
alias ...='cd ../../'
alias _='cd -'

alias gitp='git pull --rebase'
alias gitst='git status'
alias gitcl='git clone'
alias git1diff='git diff HEAD~1 HEAD'
alias gitcmt='git commit'
alias gitpo='git push origin'

alias sha1='openssl sha1'
alias sha256='openssl sha1 -a 256'
```

[A full verison](https://github.com/WalterInSH/dotfile/blob/master/MACOSX/bash_aliases)

## Nice HTTP API development tools

* [postman](https://www.getpostman.com/)

## Nice file preview tools

* [quicklook-json](http://www.sagtau.com/quicklookjson.html)
* [quicklook-csv](https://github.com/p2/quicklook-csv)

```
brew cask install quicklook-json quicklook-csv
```

## Powerful mind mapping tools

* [xmind](http://www.xmind.net/)

