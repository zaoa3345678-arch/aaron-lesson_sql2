#README.md
# Install
. Git
. DB Browser for SQLite

# Linux command
mkdir [folder.name] #create new folder in currnet directory
cd [folder.name] # go to next level folder in current directory
cd .. # go to 1 stage high root of current directory
ls # show file and folder list of current directory

# Initialize Environment
- in terminal
. git --version
. git config --global user.name 'Aaron Hon-Yu Ma'
. git config --global user.email 'hyma128@pu.edu.tw'
. git init

# Common Used Instruction
. git status
. git log --oneline

# Track File and Folder
create a new README.md file, ctrl + S
. git add [full file name]
. git add *.file_sub_name
. git add .
. git commit -m 'message'

# Supplementary: others instruction of modify file
. git reset --soft HEAD~ #回到上一動/canceling commit
. git reset --hard [version.number]
. git diff [version.number] -- [filename]
. git checkout [version.num] -- [filename]