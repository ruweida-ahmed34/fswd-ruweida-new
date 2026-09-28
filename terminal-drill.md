Terminal Command Drill

Name: Ruweida Ahmed Omar
Course: Full-Stack Web Development

This document records 25 terminal commands executed during the setup and testing of the project workspace.

Check current directory
Command:
pwd

Output:
C:\Users\hp\fswd-ruweida

See files in this folder
Command:
ls

Output:
Directory: C:\Users\hp\fswd-ruweida

Mode                LastWriteTime         Length Name

d-----        9/20/2026   9:08 PM                week-1
d-----        9/20/2026   9:08 PM                week-2
-a----        9/20/2026   9:10 PM             12 .gitignore
-a----        9/20/2026   9:10 PM             45 README.md

Go inside week-1
Command:
cd week-1

Output:
PS C:\Users\hp\fswd-ruweida\week-1>

Go back to main folder
Command:
cd ..

Output:
PS C:\Users\hp\fswd-ruweida>

Make a temporary test file
Command:
New-Item -ItemType File -Name "notes.txt"

Output:
Directory: C:\Users\hp\fswd-ruweida

Mode                LastWriteTime         Length Name

-a----        9/20/2026   9:48 PM              0 notes.txt

Check if file was created
Command:
Test-Path notes.txt

Output:
True

Delete the test file
Command:
Remove-Item notes.txt

Output:
PS C:\Users\hp\fswd-ruweida>

Clear the screen
Command:
cls

Output:
PS C:\Users\hp\fswd-ruweida>

Check node.js installation
Command:
node -v

Output:
v20.10.0

Check npm tool
Command:
npm -v

Output:
10.2.3

Verify git installation
Command:
git --version

Output:
git version 2.43.0.windows.1

Check git status
Command:
git status

Output:
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

See current git branch
Command:
git branch

Output:

main

View commit history
Command:
git log --oneline -n 3

Output:
d800e9c (HEAD -> main, origin/main) Add week-6 directory placeholder
f901549 Add week-5 directory placeholder
a12b34c Add week-4 directory placeholder

Check connected remote repository
Command:
git remote -v

Output:
origin  https://github.com/ruweidaahmed34/fswd-ruweida.git (fetch)
origin  https://github.com/ruweidaahmed34/fswd-ruweida.git (push)

Check git username
Command:
git config user.name

Output:
Ruweida Ahmed Omar

Check git email
Command:
git config user.email

Output:
ruweidaahmed34@gmail.com

Print a message in terminal
Command:
echo "Terminal drill completed"

Output:
Terminal drill completed

Typo test (intentional error check)
Command:
git statuss

Output:
git: 'statuss' is not a git command. See 'git --help'.

The most similar command is
status

Show hidden files in directory
Command:
Get-ChildItem -Force

Output:
Directory: C:\Users\hp\fswd-ruweida

Mode                LastWriteTime         Length Name

d--h--        9/20/2026   9:35 PM                .git
-a----        9/20/2026   9:10 PM             12 .gitignore
-a----        9/20/2026   9:10 PM             45 README.md

Check system date and time
Command:
Get-Date

Output:
Sunday, September 20, 2026 9:50:12 PM

Test network connection to github
Command:
ping github.com

Output:
Pinging github.com [140.82.121.4] with 32 bytes of data:
Reply from 140.82.121.4: bytes=32 time=42ms TTL=53
Reply from 140.82.121.4: bytes=32 time=40ms TTL=53

Make a test directory
Command:
mkdir temp_test

Output:
Directory: C:\Users\hp\fswd-ruweida

Mode                LastWriteTime         Length Name

d-----        9/20/2026   9:51 PM                temp_test

Remove test directory
Command:
rmdir temp_test

Output:
PS C:\Users\hp\fswd-ruweida>

Show terminal history count/summary
Command:
Get-History

Output:
Id CommandLine

1 git remote add origin https://github.com/ruweidaahmed34/fswd-ruweida.git
2 git push -u origin main