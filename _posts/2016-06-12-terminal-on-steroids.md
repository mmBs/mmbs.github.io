---
layout:     post
title:      Terminal on steroids
date:       2016-06-12
summary:    This is a tutorial how to make your terminal useful and beautiful.
categories: tools terminal
---

I really like beautiful things, especially connected to my IDE or, generally speaking,
to my work environment. I believe that all neat colors and clean design really facilitate
our work. This is the reason, why I would like to focus today on making the terminal
beautiful.

This is what I achieved so far:

![My Terminal](/images/2016-06-12-terminal.png)

I would like to keep this post as simple as possible, so please find
all steps you need to take below.

## Manual

1. Install the latest version of [iTerm2 terminal](https://www.iterm2.com/).
2. Check if you have zsh already installed on your machine: `zsh --version`.
* **If no**, install zsh using e.g. `homebrew`,   
**if yes**, you need to check your version and update to the newest one.  
How to do that? [This tutorial](http://rick.cogley.info/post/use-homebrew-zsh-instead-of-the-osx-default/)
covers it in a great manner. However, for the purposes of this article, I would like to
list the main steps [^1]:    
* Check the location of zsh: `which zsh`
* Confirm the shell that’s set for your user: `dscl . -read /Users/$USER UserShell`
* Upgrade zsh with homebrew: `brew install zsh`
* Confirm brew’s zsh location: `ls -la /usr/local/bin/zs*` or `brew list` or `brew info zsh`
* Replace zsh to brew's one: `sudo dscl . -create /Users/$USER UserShell /usr/local/bin/zsh`
* Restart your terminal.
* Check again the version of zsh: `which zsh`
* Confirm you use brew's zsh: `dscl . -read /Users/$USER UserShell`
* You should be done :)
3. Install [Oh My ZSH!](http://ohmyz.sh/) using **curl**: `sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`   
or **wget**: `sh -c "$(wget https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"`
4. Change a default theme from robbyrussell to **agnoster**. To do that you need to set `ZSH_THEME` to the name of the theme in your `~/.zshrc`. [Here](https://github.com/robbyrussell/oh-my-zsh/wiki/Themes) you can find a list of preinstalled themes.
5. To set up the same font I have, first of all, you need to install **Meslo** and **Roboto** font from [powerline fonts](https://github.com/powerline/fonts). Just clone them and use `.install.sh` script. Then change the fonts in iTerm2 preferences (cmd + ,) like it is shown in the picture below:
![My text settings](/images/2016-06-12-terminal-font-preferences.png)
6. In a colors tab (iTerm2 preferences) set up color presets to `Dark Solarized`. You can find a lot of themes [here](http://iterm2colorschemes.com/).
7. To activate plugins (e.g. git plugin) you need to update this line in `.zshrc` file: `plugins=(git bundler osx rake ruby)`.
8. That's it, you're done! :)

## Explanation
You may ask, why I need to install zsh and use it instead of bash? In fact, you don't need to. But zsh gives you a lot of improvements out of the box:  

* Great prompt,
* amazingly quick and smart auto completion,
* spelling correction,
* support of many great plugins (especially for git),
* a really quick configuration with oh-my-zsh,
* many many more.

If you want to go deeper into discussion or gather more information about **oh-my-zsh**, you can visit [Quora](https://www.quora.com/What-are-the-advantages-and-disadvantages-of-using-zsh-instead-of-bash-or-other-shells). What is more, [here](https://www.quora.com/What-is-the-difference-between-bash-and-zsh) you can find a comparison between bash and zsh.

I hope the article is helpful. Please let me know about your thoughts.

## Useful links
1. [http://ohmyz.sh/](http://ohmyz.sh/)
2. [https://github.com/robbyrussell/oh-my-zsh/](https://github.com/robbyrussell/oh-my-zsh/)
3. [https://www.iterm2.com/](https://www.iterm2.com/)
4. [http://brew.sh/](http://brew.sh/)

---
[^1]: These steps come from [Rick Cogley's blog](http://rick.cogley.info/post/use-homebrew-zsh-instead-of-the-osx-default/)
