## sed command examples
#### sed
```
> sed stands for stream editor, which is used to search a word in the file and replace it with the word required to be in the outpout.
>> note: it will only modify the output, but there will be no change in the original file.
```
## Examples

```
# sed 's/<old_text>/<new_text>' <file_name> 
# sed 's/<old_text>/<new_text>/g' <file_name>
# sed -i 's/<old_text>/<new_text>' <file_name>
# sed -n '7,10p' <file_name>
# sed '7,10d' <file_name>
```
