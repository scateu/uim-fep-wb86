# uim-fep-wb86

```
sudo apt-get install uim-fep
sudo mkdir /usr/share/uim/tables
sudo cp *.table /usr/share/uim/tables/
sudo uim-module-manager --register xmload
```

```
cp .uim ~/.uim
```


```
uim-fep -u wb86 -C white:black
echo 'alias ucdos="uim-fep -u wb86 -C white:black"' >> ~/.bashrc
```

`C-\` to turn on or off input method.


## TODO

有待向Debian里增加一个uim-wb86的包


## Example

```
uim-fep -u wb86 -C white:black -e weechat irc://scateu@irc.freenode.net/#tuna,#tuna-random -r /window splitv 50
```


## 其它

/usr/share/uim/im-switcher.scm 里面，可以把wb86的提示用中文汉字改一下

    (wb86             . "五")
