# afiman
Advanced file manipulation

## Idea

Stack operations

Joins 2 directories in a new folder and delete old ones

```
add directory "~/imgs"
add directory "~/imgs2"
create folder and join all folders on the directory 
delete all on stack

a d "~/imgs" a d "~/imgs2" c a d "~/allImgs" j "~/allImgs" d S
```
or
```
add directory "~/imgs"
add directory "~/imgs2"
add directory "~/allImgs"
create folder and join all folders on the directory 
pop
delete all on stack

push d"~/imgs" d"~/imgs2" d"~/allImgs" join pop del
```
