Locale Fix
==========
This is a bash script to fix a problem I have found on certain servers. After the initial setup on my OVH hosted server, I regularly get the following error:

```
-bash: warning: setlocale: LC_ALL: cannot change locale (en_US.UTF-8)
```

This solution is pretty much just exactly what is suggested in the comments [here](http://askubuntu.com/questions/454260/how-to-solve-locale-problem)

Usage
=====

Clone the git repository
------------------------
```
git clone https://github.com/itstriz/locale-fix.git
```

Fix permissions
---------------
```
chmod 755 locale-fix.sh
```

Run the script
--------------
```
./locale-fix.sh
```


