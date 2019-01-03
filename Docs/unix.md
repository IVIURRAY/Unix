Command Line Cheat Sheet
========================

The command line is a text interface for your computer. Passing commands from the terminal to the OS. This is a list of **unix** commands for Linux based systesm such as Mac OS X.

Commands:
* `pwd` output current working directory

* `ls` list current directory contents

* `ls -a` list current directory contents including hidden files

* `ls -l` list current directory contents in long format

* `ls -t` list current directory contents sorted by time modified

* `cd` change directory, e.g `cd <dirname>` (Use tab to autocomplete)

* `cd ..` change directory up

* `cd ~` change directory to root

* `cd Documents/SomeDoc` change to this directory

* `mkdir` make directory, e.g `mkdir <dirname>`

* `touch` create a new file in current dir, e.g `touch newfile.txt`

* `cp` copy file or directory, e.g `cp somefile.txt newlocation/`

* `mv` move file into directory, e.g `mv myfile.txt somedir/`

* `rm` delete file

* `rm -r` delete directory and all children

* `cat` print output of file, e.g `cat myfile.txt`

* `echo` print this text, e.g `echo "hello, world!"`

* `nano` command line editor

* `>` take the output on the left and redirect it to the file on the right, e.g `echo "hello, world!" > emptyfile.txt`

* `>>` take the output on the left and appends it to the file on the right, e.g `cat emptyfile.txt >> somefile.txt`

* `<` take the standard input from the file on the right and inputs it into the **program** on the left, e.g `cat < somefile.txt`

* `|` pipe, take standard output from output on left and pass it as input onto the right command

* `wc` newline count, word cout and byte count.
```
$ echo "my text" | wc
1	2	8
// 1 line, 2 words, 8 bytes
```

* `alias` create keyboard shortcuts, e.g alias gday="echo How are you today?"

* `*` wildcard select all, e.g copy all file to newloc`cp * newloc/`  

* `grep` global regular expression print, regex search e.g `grep "Mount" mountains.txt`

* `grep -i` case insensitive

* `grep -R` return all filenames and lines, e.g `grep -R Mount /src/Mountains`

* `grep -RL` same as above but just filenames

* `sed` stream editor, accepts input and modifies it based on expression before displaying it as output.
```
$ sed 's/snow/rain/' forests.txt
// s: substitute
// snow: search string
// rain: replacement string
```

* `sort` takes filename or standard input and order each line alphabetically, e.g `sort lakes.txt`

* `uniq` unique, takes a filename or standard input and prints out everyline removing duplicates.

