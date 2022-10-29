# afiman
Advanced file manipulation

## Idea

Stack operations

Joins 2 directories in a new folder and delete old ones

```
add directory "~/imgs"
add directory "~/imgs2"
add directory "~/allImgs"
create folder and join all folders on the directory 
pop
delete all on stack

push d"~/imgs" d"~/imgs2" d"~/allImgs" join pop del
```

Print all files from two directories

```
push d"~/imgs" d"~/imgs2" tofiles print
```

Delete files bigger than 2g


```
push d"~/imgs" tofiles filter "size>2g" del
```
