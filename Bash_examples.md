## Commands
### cd
It is used to move between folders
e.g. 
cd Desktop

### mkdir
It is used to create folders
e.g. 
mkdir HW2

### nano  
It is used to create a file  
e.g. 
nano Test1.c  

### cp  
It is used to copy files  
e.g.  
cp File1 File2  
-cp -R: Copy the files in a recursive way  

### pwd  
It shows in what directory you are  

### cat  
Shows the content of a file  
e.g  
cat file1  

### rm  
It is used to remove a file  
e.g.  
rm file1  
-rm file*: Delletes all the files with a given name  

### mv  
It is used to move a file to other directory  
- mv file1 newfile: Change the name of the file  
- mv file1 /destination: Move the file to a destination  

### ls  
It is used to list all the elements in a folder.  
ls .*: Shows the hidden files  
ls -l: Shows the files in a list format  
ls -a: Shows all the content  
ls -A: It's the same as -a but in this command the points of the directory don't appear  
ls -Al: Combine the commands ls -l and ls -A  
ls -lh: Shows the files in a list format and gives information in a easy way  

### locate
Search in the computer the word given
e.g.
locate file1
- locate [[:lower:]] word: Search in the computer the given word but in lowercase

### find
It is used to search files in the computer  
-find . -name "file name" : Return all the routes where the file is  
-find / -name filename: Search the file in the source folder  
-find . -atime +100: Shows the files of the folder, that were open 100 days ago
-find / -name *.txt -fprint new_file_to_print.txt: Print all the .txt files in the directory specified  

### stat
Shows the statistisc of a file
-stat file1.txt 

### chmod
-chmod +x filename: Give permissions to the user
-chmod -x filename: Take out the permissions


## 5 examples of find
- find / -mtime 7
- find / -cmin -120
- find /tmp -type f -name ".*"
- find . -type f -name "*.HEIC" -exec rm -f {} \;
- find . -type f -name "file221.txt" -exec rm -f {} \;
