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

push "~/imgs" "~/imgs2" "~/allImgs" join pop del
```

Print all files from two directories

```
push "~/imgs" "~/imgs2" tofiles print
```

Delete files bigger than 2g

```
push "~/imgs" tofiles filter "size>2g" del
```

Find duplicated files

```
push "~/imgs" tofiles dupes print
```

Find duplicated files, delete first

```
push "~/imgs" tofiles dupes loop del pop endLoop
```

Replace text

```
push "~/foo.txt" "~/bar.txt" regin "s/xxx/yyy/g"
```

Replace in file name 

```
push "~/foo.txt" "~/far.txt" regname "s/f/b/g"
```

Print all file properties available for filtering

```
push "~/foo.txt" toprops print
```



