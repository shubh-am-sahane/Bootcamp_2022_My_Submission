
# Solution of Linux Exercise

## Varients of ls command:
ls : List all directries
![ls](https://user-images.githubusercontent.com/85026392/174494298-4e2a4812-8c51-4d71-bcbe-a3c4d2e8b790.jpg)


ls -l : shows files or directory, size, modified date and time, file or folder name & owner of the file, &its permission
![ls -l](https://user-images.githubusercontent.com/85026392/174494384-07e840d8-db2a-473b-aa5a-d617df31bc50.jpg)


ls -a : View hidden files
![ls3](https://user-images.githubusercontent.com/85026392/174494889-79531017-b089-4008-8fad-3a67276260ee.jpg)


ls -lb : list files in human readable form
![4](https://user-images.githubusercontent.com/85026392/174495038-88665e57-8cf9-4e3e-8f61-0e080d6fd810.jpg)



ls -F : list files and direc with '/' char at the end
![5](https://user-images.githubusercontent.com/85026392/174495065-10955f64-1cb6-4804-8e4f-dbb8e8138027.jpg)



ls -r : list files in reverse order
![6](https://user-images.githubusercontent.com/85026392/174495092-2436e2ab-7226-4744-98d3-de069ca5d4fd.jpg)


ls --help : shows ls command help page
![7](https://user-images.githubusercontent.com/85026392/174495110-3d1b2d7a-b56b-45dd-aad0-e0ae658d2a8b.jpg)


## Varients of cp:

cp -a : archive files

cp -f : Force copy by removing the designation file if needed

cp -i : Iteractive - ask before overrite

cp -l : link file instead of copying

cp -L : follow symbolic link

cp -n : No file overite

cp -R : recursive copy

cp -u : update

cp -v : print information message

### Copy single file to directory :

cp hello.c temp

### Copy multiple files :
cp hello.c sum.c temp

### Copy all files :
cp *.c temp

