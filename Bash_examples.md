## Command
s
### cd
It is used to move between folders
e.g. 
- _cd_ Desktop

### mkdir
It is used to create folders
e.g. 
- _mkdir_ HW2

### nano  
It is used to create a file  
e.g. 
- _nano_ Test1.c  

### cp  
It is used to copy files  
e.g.  
- _cp_ File1 File2  
- _cp_ -R: Copy the files in a recursive way  

### pwd  
It shows in what directory you are  

### cat  
Shows the content of a file  
e.g  
- _cat_ file1  

### rm  
It is used to remove a file  
e.g.  
- _rm_ file1  
- _-rm_ file*: Delletes all the files with a given name  

### mv  
It is used to move a file to other directory  
- _m_v file1 newfile: Change the name of the file  
- _mv_ file1 /destination: Move the file to a destination  

### ls  
It is used to list all the elements in a folder.  
- _ls_ .*: Shows the hidden files  
- _ls_ -l: Shows the files in a list format  
- _ls_ -a: Shows all the content  
- _ls_ -A: It's the same as -a but in this command the points of the directory don't appear  
- _ls_ -Al: Combine the commands ls -l and ls -A  
- _ls_ -lh: Shows the files in a list format and gives information in a easy way  

### locate
Search in the computer the word given
e.g.
- _locate_ file1
- _locate_ [[:lower:]] word: Search in the computer the given word but in lowercase

### find
It is used to search files in the computer  
- _find_ . -name "file name" : Return all the routes where the file is  
- _find_ / -name filename: Search the file in the source folder  
- _find_ . -atime +100: Shows the files of the folder, that were open 100 days ago
- _find_ / -name *.txt -fprint new_file_to_print.txt: Print all the .txt files in the directory specified  

### stat
Shows the statistisc of a file
- _stat_ file1.txt 

### chmod
-_chmod_ +x filename: Give permissions to the user
-_chmod_ -x filename: Take out the permissions


## 5 examples of find
- _find_ / -mtime 7
- _find_ / -cmin -120
- _find_ /tmp -type f -name ".*"
- _find_ . -type f -name "*.HEIC" -exec rm -f {} \;
- _find_ . -type f -name "file221.txt" -exec rm -f {} \;

### sort

