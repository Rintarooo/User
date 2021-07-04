# My Sublime text settings

[command]+[shift]+[P]
brings up the Command Palette

In Command Palette, 
`Package Control: List Packages`, you can see the packages already installed

`Package Control: Install Package` , you can install the package

`Package Control: Remove Package` , you can remove the package already installed

## Install on Linux and MacOS
download Sublime text 4 from [official site](https://www.sublimetext.com/download)

## Set up
### Linux
  
`$ cd ~/.config/sublime-text-4/Packages/`
  
`$ git clone https://github.com/Rintarooo/User.git`
  
make sure path is `~/.config/sublime-text-3/Packages/User/` by `$ pwd`
  
launch sublime by `$ subl`
  
might need to change the compile path in a file in `./my_BuildSystem/`
  
  
### MacOS
  
launch sublime by `$ subl`
  
if this command doesn't work, create a symbolic link `$ sudo ln -s /Applications/Sublime\ Text.app/Contents/SharedSupport/bin/subl /usr/local/bin/subl`
  
make sure PATH includes `/usr/local/bin/` by using `echo $PATH`

`$ cd ~/Library/Application Support/Sublime Text/Packages/`
  
`$ git clone https://github.com/Rintarooo/User.git`
  
make sure path is `~/Library/Application Support/Sublime Text/Packages/User/` by `$ pwd`

## Color Scheme
recommended color scheme

[command]+[shift]+[P] -> UI: Select Color Scheme
* candy crush


## Reference
* https://packagecontrol.io/docs/syncing
* https://qiita.com/mokmokjp/items/14c420ef9664999eb94b (written in Japanese)

