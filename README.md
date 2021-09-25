# dirDate
Bash script to set the date of a directory to the latest date of any contained file

~~~
Usage: dirDate [options] directory ...
        update directory's date/time to be that of the most recently
        changed contained file/folder
        Options:

        --help          show this help screen
        --verbose       control message level (repeat for more information)
        --quiet         control message level (repeat for less information)
        --norecurse     don't update subdirectory date/times
        --test          test mode (say what will be done, don't do it)

        short options use the initial letter of long options:
        -hvqt
~~~
