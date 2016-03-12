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
echo 'alias ime="uim-fep -u wb86 -C white:black"' >> ~/.bashrc
echo 'alias ucdos="uim-fep -u wb86 -C white:black"' >> ~/.bashrc
```


`C-\` to turn on or off input method.


## TODO

有待向Debian里增加一个uim-wb86的包


