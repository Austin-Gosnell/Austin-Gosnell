## Lab 01

- Name: Austin Gosnell
- Email: gosnell.4@wright.edu

Instructions for this lab: https://pattonsgirl.github.io/CEG2350/Labs/Lab01/Instructions.html

## Part 1 - GitHub Profile

1. https://github.com/Austin-Gosnell

## Part 2 - Research

| Windows | Linux / Mac | Action |
| ---     | ---         | ---    |
| help    | man         |   describes and gives options for commands     |
| Get-Location | pwd    |    prints working directory. Tells the current file path    |
| Get-ChildItem | ls    |  list files in current directory      |
| mkdir   | mkdir       |    make directory. creates folder directory    |
| Set-Location | cd     |    change which directory you're working in    |
| New-Item | touch      |   creates file folder     |
| Move-Item | mv        |    rename or move files and directories    |
| Copy-Item | cp        |    copy files or directories    |
| Remove-Item | rm      |     permanently delete files   |
| notepad.exe | vim     |     open or create file in text editor   |

## Part 3 - Command Line Navigation

My OS is:
- [x] Windows
- [] Linux
- [] Mac

My Command Line Shell is: Ubuntu

### Navigating My OS on the Command Line

1. Full / absolute path to your user's home directory: pwd
2. Create a directory named `DirA`: mkdir DirA
3. Create a directory named `Dir B`: mkdir "Dir B"
4. Go into `DirA`: cd DirA
5. Go into `Dir B` from `DirA`: cd .. , cd "Dir B"
6. Return to your user's home directory: cd 
7. Create a file named `test.txt`: touch test.txt
8. Move the file named `test.txt` into `DirA`: mv test.txt DirA
9. Contents of `test.txt`: vim test.txt
```
[I]
hopefully this text saves
[esc]
:wq
```
10. Make a copy of `test.txt` named `copy.txt` in `DirA`: cp test.txt copy.txt
11. View the contents of `DirA`: ls
12. Make a copy of `test.txt` in `Dir B` named `fodder.txt`:cp test.txt fodder.txt , mv fodder.txt ../ , mv fodder.txt "Dir B"
13. Delete / remove both `fodder.txt` AND `Dir B`: cd "Dir B" , rm fodder.txt , cd , rmdir "Dir B"

## Citations

https://www.geeksforgeeks.org/linux-unix/basic-linux-commands/
gave me a brief description of the commands that had not already been discussed in class