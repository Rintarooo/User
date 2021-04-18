# My Sublime text 3 settings

[command]+[shift]+[P]
brings up the Command Palette

`List Packages` in Command Palette
see the packages already installed

## Install on Linux

download Sublime text 3 from [official site](https://www.sublimetext.com/3)
  
`$ cd ~/.config/sublime-text-3/Packages/`
  
`$ git clone https://github.com/Rintarooo/User.git`
  
make sure path is `~/.config/sublime-text-3/Packages/User/`
  
launch sublime by `$ subl`
  
might need to change the compile path in a file in `./my_BuildSystem/`
  
  
## Install on Mac
  
launch sublime by `$ subl`
  
if this command doesn't work, create a symbolic link `$ ln -s /Applications/Sublime\ Text.app/Contents/SharedSupport/bin/subl /usr/local/bin/subl`
  
make sure PATH includes `/usr/local/bin/` by using `echo $PATH`

## Reference
* https://packagecontrol.io/docs/syncing
* https://qiita.com/mokmokjp/items/14c420ef9664999eb94b (written in Japanese)

