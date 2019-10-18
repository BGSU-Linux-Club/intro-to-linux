# Linux for CS Classes and Beyond Demonstration Notes

_Note to future readers_: These are a rough outline for the demonstration and are in the repo for completeness sake. Use `man` instead to get a better understanding of what each command does.

### `man`
  + Short for Manual
  + Gives just about everything you need to know about a command

### `clear`
  + Hides the contents above the top of the window
  + Use `tput reset` to delete all the previous commands from the terminal

### `ls`
  + Lists out the contents of your current directory
  + `-a` includes hidden files and directories, and `..`, `.` directories.
  + '-l' includes file permissions, owner and group, size, and last modified date
  + If given a path argument it will list the contents of the given directory

### `cd`
  + Abbreviation of change directory
  + Takes a relative or absolute path as an argument, and changes your current directory to the given one
  + Current directory is labeled `.`
  + Parent directory is labeled `..`

### `pwd`
  + Prints the absolute path of the current directory


### `less`
  + Displays the contents of a given file in the terminal, in a non-writable format
  + Faster and less hassle than terminal text editors
  + Exit by pressing `q`

### `touch`
  + Creates a file by the given name

### `mkdir`
  + Makes a directory with the name given

### `mv`
  + Moves (renames) the file at the path of the first argument, to the location of the path in the second argument

  + `mv <current location> <new location>`

### `rm`
  + Deletes files and folders
  + `rm -rf` to delete a folder and all of its contents

### Terminal Text Editors
  + `vi`
    + `:q` to exit
  + `vim`
    + `:q` to exit
  + `emacs`
    + `ctrl + x, c` to exit

  + Vi is the simplest, but there's not much difference between vim and emacs. 
