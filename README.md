# fec : file extension counter

Tiny utility to compute recursively the number of files of each type in a
directory.

## Usage

```sh
user@host$ fec -r my_directory  # 'r' option to sort in descending order
.pdf        76
.md         8
.html       5
.gitignore  1
```

## Credits

Credits to [this
answer](http://serverfault.com/questions/183431/get-all-extensions-and-their-respective-file-count-in-a-directory)
on *Server Fault* for the original one liner.
