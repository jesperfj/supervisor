Set up supervisord on Raspberry Pi (and probably works on other UNIXy OSes).

supervisord is set up to run as the pi user (not root). 

# Usage

Clone this repo down to the machine where you want to do the deed:

```
$ ssh pi@mypi
...
$ mkdir apps # I like storing all my "managed" stuff in an apps dir
$ cd apps
$ git clone https://github.com/jesperfj/supervisord
...
$ cd supervisord
$ ./install
```

The install script uses sudo commands so you need sudo privileges.


