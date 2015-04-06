ggl
===
Google right from your command line
-----------------------------------

Do you ever need to perform a quick google search while on command line?
Well that's exactly what ggl is for, it lets you open your browser on your query without the hassle. You can also search Google Images, YouTube and Stackoverflow. See usage for more info.

Installation
------------
```sh
gem install ggl
```

If you're not on OSX you need to have ```xdg-open``` installed.

Usage
-----
```sh
ggl [query]                          simple google search
ggl -i/--images [query]              google images search
ggl -y/--youtube [query]             youtube search
ggl -s/--stack/--stackoverflow       search stackoverflow (oh yes)
ggl -b/--baidu                       search baidu (国情需要)
ggl -g/--gfsoso                      search gfsoso (若谷歌被墙，还有谷粉搜搜)

```
License
-------

Copyright 2015 Justyna Rachowicz

This project including all of its source files is released under the terms of GNU General Public License (version 3 or later)
