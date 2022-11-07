# heroku-buildpack-python-libcurses

Sets `python2.7` as the default `python` executable without superuser privileges, and adds a path containing`libncurses.so.5` to `$LD_LIBRARY_PATH`. Only runs if `python2.7` is present.
