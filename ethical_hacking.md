# Linux Operating System
## Navigate Through Linux System
```
# to home directory ~
cd
cd Documents

# print working directory /home/kali
pwd

# to main directory /
cd ..
cd ..

# list, in main show all standard linux directories & files, etc home ...
ls
cd etc
```
## Create Files & Manage Directories
```
# create empty file
touch file1

# show file content
cat file1

# add content to exist file by nano 
echo  hello world > file1

# create and add content by nano, but can not create empty file
nano file2

# create and add content by vim, need advance vim skill
vim file3

# create folder
mkdir folder1

# move file
mv file2 folder1

# copy file
cp file3 file4
cp file3 ..
cp file3 folder1/file5

# remove file
rm file3
rm *
rm -r folder1
rm -r *

# create simple py file and run it: print("hello world")
nano file5.py
python3 file5.py
```
