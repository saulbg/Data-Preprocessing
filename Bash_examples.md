## Commands

### cd
It is used to move between folders
e.g. 
- __cd__ Desktop

### mkdir
It is used to create folders
e.g. 
- __mkdir__ HW2

### nano  
It is used to create a file  
e.g. 
- __nano__ Test1.c  

### cp  
It is used to copy files  
e.g.  
- __cp__ File1 File2  
- __cp__ -R: Copy the files in a recursive way  

### pwd  
It shows in what directory you are  

### cat  
Shows the content of a file  
e.g  
- __cat__ file1  

### rm  
It is used to remove a file  
e.g.  
- __rm__ file1  
- __-rm__ file*: Delletes all the files with a given name  

### mv  
It is used to move a file to other directory  
- __mv__ file1 newfile: Change the name of the file  
- __mv__ file1 /destination: Move the file to a destination  

### ls  
It is used to list all the elements in a folder.  
- __ls__ .*: Shows the hidden files  
- __ls__ -l: Shows the files in a list format  
- __ls__ -a: Shows all the content  
- __ls__ -A: It's the same as -a but in this command the points of the directory don't appear  
- __ls__ -Al: Combine the commands ls -l and ls -A  
- __ls__ -lh: Shows the files in a list format and gives information in a easy way  

### locate
Search in the computer the word given
e.g.
- __locate__ file1
- __locate__ [[:lower:]] word: Search in the computer the given word but in lowercase

### find
It is used to search files in the computer  
- __find__ . -name "file name" : Return all the routes where the file is  
- __find__ / -name filename: Search the file in the source folder  
- __find__ . -atime +100: Shows the files of the folder, that were open 100 days ago
- __find__ / -name *.txt -fprint new_file_to_print.txt: Print all the .txt files in the directory specified  

### stat
Shows the statistisc of a file
- __stat__ file1.txt 

### chmod
- __chmod__ +x filename: Give permissions to the user
- __chmod__ -x filename: Take out the permissions


## 5 examples of find
- __find__ / -mtime 7
- __find__ / -cmin -120
- __find__ /tmp -type f -name ".*"
- __find__ . -type f -name "*.HEIC" -exec rm -f {} \;
- __find__ . -type f -name "file221.txt" -exec rm -f {} \;

### sort
It is used to sort or merge lines of text and binary files  
- __sort__ filename: Sort the lines alphabetically  
_ __sort__ -n: Sort the lines numerically by arithmetic value  
- __sort__ -n -r: Sort the lines numeric in regressive (descending)  

### grep  
It is used to find patterns, selecting  lines that match one or more patterns
e.g.  
- __grep__ namefile

### tail  
Display the last linest of a file  
e.g.
- __tail__ filename
- __tail__ -n # filename: Display the last n numbers of a file  

### head  
Display the firs lines of a file  
e.g.
- __head__ filename: shows the first 10 lines  
- __head__ -n # filename: shows the first n lines  


### touch  
It is used to set the modification and access times of files  


### stat  
It is used to display file status  
e.g.  
- __stat__ filename


### cut  
It is used to cut out selected portions of each line of a file  
e.g
- __cut__ -d "," -f3 filename: Cut the element on the field 3 between the delimiter ","    

