# Mac Terminal
![](https://github.com/kakshay21/mac-terminal/blob/master/image.png)

## iTerm 2 :
Firstly, download and install iTerm2. It's a free replacement for the default terminal that comes with your OS X installation. The installation is pretty straightforward.

## ZSH ( Z Shell ):
Zsh is a shell designed for interactive use though it's also a powerful scripting language.
To install Oh My Zsh ( Zsh Framework), just run below command in your iTerm2 terminal.
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

```
Visit their GitHub page for more information.
## Solarized Color Scheme
To get the color scheme just like the one used in this tutorial (Solarized), you can run following command :
```
curl -o ~/Desktop/solarized.itermcolors https://raw.githubusercontent.com/altercation/solarized/master/iterm2-colors-solarized/Solarized%20Dark.itermcolors

```

This will download the latest Solarized Dark Colors scheme to your desktop. You can then open up the iTerm's preferences pane, select Profiles, select the Colors tab and click load presets > import and choose the solarized.itermcolors file from your desktop.
After successfully importing the scheme file, you can pick the theme from same dropdown.

## Meslo Font
I'm using the Powerline Meslo Font, which is a really nice and comes with variety of symbols that are used in Zsh prompt. To install Powerline fonts, run the following command :
```
git clone https://github.com/powerline/fonts.git && cd fonts && ./install.sh

```
Now From iTerm's preferences pane, click profiles again, go into Text tab and change the font to Meslo LG L Regular For Powerline. You can also play around other Powerline fonts.
