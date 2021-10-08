# Coursera-DE-C2-Lab4-Composing-File-Data-Solutions
Composing File and Data Solutions with Linux

## Goal:   Search the filesystem with the find command

Now that you have learned to search with the `find` command let's put this to use.

### Part 1: Search with find

1.  Search the /bin directory and count the number of file you find `find /usr/bin | wc -l`
2.  Find the location of python versions on your system:  `find /usr/bin | grep python`
3.  How could you change the last command to find a specific version of Python?

### Part 2:  Search for file types

1.  Search for all of the csv files in `docs` `find -name "*.csv"`
2.  How many did you find?
3.  Can you search for files with the `.txt` extension?  How many do you find?