## Lab 01

- Name: Mandy Howard
- Email: howard.432@wright.edu

Instructions for this lab: https://pattonsgirl.github.io/CEG2350/Labs/Lab01/Instructions.html

## Part 1 - GitHub Profile

1. [mandyhoward21’s GitHub Profile](https://github.com/mandyhoward21)

## Part 2 - Research

| Windows | Linux / Mac | Action |
| ---     | ---         | ---    |
| help    | man         |   Displays help about Windows PowerShell cmdlets and concepts.   |
| Get-Location | pwd    |   Shows path   |
| Get-ChildItem | ls    |   A directory of folders that are in your current location     |
| mkdir   | mkdir       |   Creates a directory/folder     |
| Set-Location | cd     |   Changes directory     |
| New-Item | touch      |   Used to create new files and folders    |
| Move-Item | mv        |   Moves files/folders from one place to another    |
| Copy-Item | cp        |   Makes a copy of an item     |
| Remove-Item | rm      |   Deletes an item    |
| notepad.exe | vim     |   Opens a plain text editor     |

## Part 3 - Command Line Navigation

My OS is:
- [x] Windows
- [] Linux
- [] Mac

My Command Line Shell is: Windows PowerShell

### Navigating My OS on the Command Line

1. Full / absolute path to your user's home directory: C:\Users\penni

2. Create a directory named `DirA`: mkdir 'DirA'

3. Create a directory named `Dir B`: mkdir 'Dir B'

4. Go into `DirA`: cd DirA

5. Go into `Dir B` from `DirA`: cd ..\Dir B

6. Return to your user's home directory: cd ..

7. Create a file named `test.txt`: New-Item 'test.txt'

8. Move the file named `test.txt` into `DirA`: Move-Item 'test.txt' 'DirA'

9. Contents of `test.txt`: notepad.exe test.txt
```
I trust myself and my ability to figure things out. 
```
10. Make a copy of `test.txt` named `copy.txt` in `DirA`: Copy-Item 'test.txt' 'copy.txt'

11. View the contents of `DirA`: ls

12. Make a copy of `test.txt` in `Dir B` named `fodder.txt`: Copy-Item "test.txt" "..\DirB\fodder.txt"

13. Delete / remove both `fodder.txt` AND `Dir B`: Remove-Item 'Dir B'


## Citations

To add citations, provide the site and a summary of what it assisted you with.  If generative AI was used, include which generative AI system was used and what prompt(s) you fed it.

Powershell used to show actions of commands.
Googled computer jokes for #9: https://www.facebook.com/groups/542942581191814/posts/1033339372152130/

