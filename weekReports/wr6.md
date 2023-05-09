---
name: Clevis Mota
semester: Spring 23
course: cis106
---

# Week Report 6

## Wildcards

### * Wildcard
The * (asterisk) wildcard matches from 0 to any number of characters.
* Examples:
  * List all the text file in a directory
    * `ls *.txt`   
  * List all the files that start with the word file
    * `ls file.*`
  * Copy all the mp4 files
    * `cp Downloads/*mp4 ~/Videos/Movies/`     


### ? Wildcard
The ? (question mark) wildcard matches precisely one character
* Examples:
  * List all hidden files
    * `ls .??*` 
  * List all hidden files in the parent directory
    * `ls ../.??*`
  * List all the files that have a 3 letter file extension
    * `ls *.???`   

### [ ] Wildcard
The [ ] (brackets) wildcard match a single character in a range. Add the exclamation mark to reverse the match.
* Examples:
  * Match all files that have a vowel after letter f 
    * `ls f[aeiou]*`
  * Match all files whose name has at least one number
    * `ls *[0-9]*`  
  * Match all files whose name begins with any of these two sets of characters: letters from a-f or p-z
    * `ls [a-fp-z]*`  

### Brace Expansion  
Brace expansions { } is not a wildcard nut has another feature of bash that allows you to generate arbitrary strings to use with commands
* Examples:
  * Create a whole directory structure in a single command
    * `mkdir -p music/{jazz,rock}/{mp3files,videos,oggfiles}/new{1..3}`
  * Create a N number of files 
    * `touch website{1..5}.html`
  * Remove multiple files in a single directory
    * `rm -r {dir1,dir2,dir3,file.txt,file.py}`     



