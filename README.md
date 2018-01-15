## Scripts

#### texenv

Initialize report writing environment

[code](texenv)

Usage:
~~~ bash
$ texenv (newdir) #=> create working directory
$ cd (newdir)
$ make init #=> create tex sources
~~~

You can use a option -i to automatically run `make init`.
~~~bash
$ texenv -i (newdir) #=> create working directory and initialize
~~~

#### javalipse

rebuild Java project for eclipse(!UNMAINTAINED!)

[code](javalipse)

Usage:
~~~ bash
$ javalipse (directory name)
~~~

#### tenki

get weather forecast from weather.livedoor.com

[code](tenki)

Usage:
~~~ bash
$ tenki [<OPTION>] [<AREA>]
~~~

Supported area:
~~~
akita fukuoka hiroshima kanazawa kochi
kushiro nagano nagoya okinawa osaka
saitama sapporo sendai tokyo yokohama
~~~
and you can add more areas

#### gitch

ssh/https switcher on git repogitory

[code](gitch)  
[code(remote name supported version)](https://github.com/tex2e/dotfiles/blob/master/bash/gitch.sh)

Usage(on git directory):
~~~bash
$ gitch
~~~

#### chcolor

prompt switcher by sourcing dotfiles (.zshrc_XXX)

[code](chcolor)

Require:
* An environmental variable `PROMPT_COLOR_SWITCH` is exported
* your dotfiles available

Usage:
~~~bash
$ chcolor
~~~

#### setsubl

sublime setting deployer(~/.dotfiles/doc/Preferences.sublime-settings)

[code](setsubl)

Usage:
~~~
$ setsubl
~~~

#### guid

get unique 32-bit key (GUID)

[code](guid)

Usage:
~~~
$ guid
~~~


#### committer

generate simple commite message

[code](committer)

Usage:
~~~
git commit -<m|am> "$(committer)"
~~~

#### csubl

wrapper to open directory for subl

[code](csubl)

Usage:
~~~
csubl <dir>
~~~