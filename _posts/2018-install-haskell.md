

Haskell is fundamentally remarkably well-designed programming languarage; unfortunately, getting Haskell installed and set up on your OS might be enough to scare the hell you far far away. I believe you know what I'm saying.

If you are using OSX, here is the way to avoid that problem.



## Don NOT touch this Haskell platform

![alt text](https://i.imgur.com/7uG42FC.png "Logo Title Text 1")


[If you did, Uninstall it.](https://mail.haskell.org/pipermail/haskell-cafe/2011-March/090170.html)

[Why? It is considered harmful](https://mail.haskell.org/pipermail/haskell-community/2015-September/000014.html)

The only thing you need to download is Stack. It will install everything else for you.

## Install Stack (OSX)

I recommend to use [brew](https://brew.sh/) to install Stack:

If you already install brew, then open your Terminal/iTerm:

```
~ % brew update


*~ % brew doctor*

Your system is ready to brew.

~ % brew install haskell-stack

==> Downloading https://homebrew.bintray.com/bottles/haskell-stack-1.6.3.high_si
######################################################################## 100.0%
==> Pouring haskell-stack-1.6.3.high_sierra.bottle.tar.gz
🍺  /usr/local/Cellar/haskell-stack/1.6.3: 6 files, 89.1MB

~ % stack --version   --- Check

Version 1.6.3 x86_64 hpack-0.20.0
```

If you wanna restart: [Uninstall Stack](https://www.reddit.com/r/haskell/comments/6z06ih/how_to_uninstall_stack/)

