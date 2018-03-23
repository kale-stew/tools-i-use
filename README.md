# Tools I Use

I just had to reformat my MBP over the weekend and it's likely I'll have to do it again in the future. This repository is where I stash names of tools and software that I use on my own machine.

## Applications

- [1Password](https://1password.com/)
- [CCleaner](https://www.ccleaner.com/ccleaner/download)
- [Discord](https://discordapp.com/download)
- [Docker](https://docs.docker.com/install/)
- [GIMP](https://www.gimp.org/downloads/)
- [MindNode](https://mindnode.com/mindnode/mac)
- [Google Earth Pro](https://www.google.com/earth/desktop/)
- [Postman](https://www.getpostman.com/)
- [Rocket](http://matthewpalmer.net/rocket/)
- [Slack](https://slack.com/downloads/)
- [SQLTabs](https://www.sqltabs.com/)
- [SelfControl](http://selfcontrolapp.com/)
- [StrongVPN](https://strongvpn.com/setup.html)
- [VLC](https://www.videolan.org/vlc/)
- [Vuze](https://www.best-bittorrent-vpn.com/how-to-use-vuze-anonymously.html) (but I should probably stop using it)
- [zoom.us](https://zoom.us/download)

## DevTools

**Editor:** [Visual Studio Code](https://code.visualstudio.com/download)

<!-- **Editor Theme:** -->

**Terminal:** [iTerm](https://www.iterm2.com/)

<!-- **Terminal Theme:** -->

**Shell:** plain 'ol bash

## Chrome Extensions

- [1Password](https://agilebits.com/onepassword/extensions)
- [appear.in](https://chrome.google.com/webstore/detail/appearin-screen-sharing/bodncoafpihbhpfljcaofnebjkaiaiga?hl=en)
- [honey](https://www.joinhoney.com/)
- [JSONView](https://chrome.google.com/webstore/detail/jsonview/chklaanhfefbnpoihckbnefhakgolnmc?hl=en)
- [Lighthouse](https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk?hl=en)
- [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=en)
- [Redux Devtools](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd?hl=en)
- [WhatFont](https://chrome.google.com/webstore/detail/whatfont/jabopobgcpjmedljpbcaablpmlmfcogm?hl=en)
- [ZenHub](https://chrome.google.com/webstore/detail/zenhub-for-github/ogcgkffhplmphkaahpmffcafajaocjbd?hl=en-US)

## VsCode Extensions

  ![extensions-list](https://github.com/kale-stew/tools-i-use/blob/master/assets/vscode-extensions.png)

## Bash Profile

```
parse_git_branch() {
    git branch 2> /dev/null | sed -e '/^[^*]/d' -e 's/* \(.*\)/ (\1)/'
}

export PS1="\u \[\033[0;36m\]\W\[\033[0;32m\]\$(parse_git_branch)\[\033[00m\] 🔥  "
```