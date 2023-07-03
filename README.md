# artixann

A viewer for the Artix Linux news feed, written in bash

### Usage:

    artixann [options]

    Options:
      -h, --help              show this message and exit
      -w, --wrapsize <width>  maximum line width. defaults to current console width
      -c, --nocolor           do not print in color. default is colorized output
      -b, --brief             do not print body of each news
      -i, --infile <path>     read news feed from file. use - for stdin
      -u, --unread            display only previously unread news
      -s, --since <days>      display news going back the given number of days
      -n, --number <number>   show this number of items. defaults to all
      -l, --url               resolve titles as hyperlinks
      -f, --fold              use fold instead of internal word wrap
