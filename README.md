tmux conf
=====

I use [Tmux](https://tmux.github.io/) as my terminal multiplexer. Many others like to use [GNU Screen](https://wiki.archlinux.org/index.php/GNU_Screen), but I found myself in using Tmux. 

How to install this?
-----
First, install it. On your Mac, you can use Homebrew:
```
$ brew install tmux
```
On Ubuntu or Debian users can user apt-get:
```
$ sudo apt-get install tmux
```
Second, clone this repository to your local machine or wherever you want to run tmux:
```
git clone https://github.com/kentsay/tmuxconf
```
Last, copy the .tmux.conf under your directory.
```
cp tmuxconf/tmux.conf ~/.tmux.conf
```

Now we're ready to use Tmux. Start up a new Tmux session:
```
$ tmux
```
Here we go!

Tmux cheat sheet
-----
You can check out more usage of using Tmux from [here](./tmux-cheat-sheet.md).
