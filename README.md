## Lab 01

- Name: Alexander Granville  
- Email: ahgranville@gmail.com

## Part 1 - GitHub Profile

1. [AGranville1](https://github.com/AGranville1)
2. [Gorph111126](https://github.com/Gorph111126)

## Part 2 - Research

| Windows | Linux / Mac | Action |
| ---     | ---         | ---    |
| help    | man         | gives help for the current command       |
| Get-Location | pwd    | Gets the current directory that you are in |
| Get-ChildItem | ls    | Gets the directories that are in the current directory|
| mkdir   | mkdir       | makes a directory with the given name in the given directory (optional)       |
| Set-Location | cd     | change what directory you are in. you can use the absolute path, or a relative path of /users/agranville/docs/file1 or if you are in /docs currently you can set-location file1       |
| New-Item | touch      | creates a new file       |
| Move-Item | mv        | moves a selected file to a specific file path       |
| Copy-Item | cp        | coppies a specific file to a specific file path       |
| Remove-Item | rm      | deletes the specified file        |  
| notepad.exe | vim     | openes the specified file in a txt editor.       |

## Part 3 - Command Line Navigation

My OS is:
- [x] Windows
- [] Linux
- [] Mac

My Command Line Shell is: powershell

### Navigating My OS on the Command Line

1. Full / absolute path to your user's home directory: C:\Users\ahgra\documents\github\lab-1
2. Create a directory named `DirA`: mkdir DirA
3. Create a directory named `Dir B`: mkdir 'Dir B'
4. Go into `DirA`: cd DirA
5. Go into `Dir B` from `DirA`: cd ../'Dir B'
6. Return to your user's home directory: cd ..
7. Create a file named `test.txt`: touch test.txt   
8. Move the file named `test.txt` into `DirA`: mv test.txt DirA
9. Contents of `test.txt`: notepad.exe DirA/test.txt
```
Keep it up, you got this!
```
10. Make a copy of `test.txt` named `copy.txt` in `DirA`: cp DirA/test.txt DirA/copy.txt
11. View the contents of `DirA`: ls DirA
12. Make a copy of `test.txt` in `Dir B` named `fodder.txt`: cp DirA/test.txt "Dir B/fodder.txt"
13. Delete / remove both `fodder.txt` AND `Dir B`: rm "Dir B" -r

## Citations

I have taken courses that have gone over this topic.



