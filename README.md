#sctech-vim#

##How to use
1. Clone the vim settings repository to the home directory:
```
git clone https://github.com/sctech/sctech-vim.git
```
2. cd to `sctech-vim` directory and run `update.sh` to get the lastest version of modules:
```
cd sctech-vim
bash update.sh
```
3. make a symbolic link `.vim` to `sctech-vim`, `.vimrc` to `.vim/vimrc`:
```
ln -s sctech-vim .vim
ln -s .vim/vimrc .vimrc

```

##Ultisnips
Ultisnips documents
```
:help UltiSnips
```
Creat costumized snippets
```
:UltiSnipsEdit
```
##Some tips
open files in split windows
```
$vim -o file1.txt file2.txt file3.txt   #open files split horizontally
$vim -O file1.txt file2.txt file3.txt   #open files split vertically
```
