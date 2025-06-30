# Basic Commands of Linux and their Purposes

## File & Directory Commands

- To Create file
```
sudo nano filename.txt
``` 
- To Create folder
```
sudo mkdir folder_name
```
- To Delete files or folders
```
sudo rm -rf filename.txt folder_name
```
- Show current directory (Print Working Directory)
```
pwd
```
- List files and folders in current directory
```
ls
```
- Long listing with details
```
ls -l
```
- Show hidden files
```
ls -a
```
- Change directory
```
cd 
```
- Remove empty directory
```
rmdir
```
- Create empty file
```
sudo touch newfile.txt
```
- Copy files or folders
```
sudo cp [source] [destination]
sudo cp from_file.txt to_file.txt
```
- Move or rename files/folders
```
sudo mv [source] [destination]
sudo mv from_file.txt to_file.txt
```

## File Viewing & Editing

- View file content
```
cat filename.txt
```
- View first 10 lines
```
head -n 10 filename.txt
```
- View last 10 lines
```
tail -n 10 filename.txt
```
- Advanced text editor (Vim)
```
sudo vi filename.txt
```
- Write text to file (overwrite)
```
echo "text" > filename.txt
```
- Append text to file
```
echo "newtext" >> filename.txt
```
