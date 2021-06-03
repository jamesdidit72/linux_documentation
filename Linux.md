### windows uses C: D: E: drives
### Linux uses root "/"
#### Linux works on the concept that everything is a file
#### one way of reading and writing
### extensions:
- used to make things clearer for the user
- linux doesnt care about extensions
    - cares about meta data
###control permissions    
| Key(s) | Description | Example |
|:---------: |:----------------------------: |:--------: |
| ls -l | prints everything in the file path |  |
| sudo | allows for root commands to execute |  | 
| chmod | changes the permissions |  |
| chown | changes the ownership | chmod 000 filename | 
| cat/etc/passwd | prints all available users |  |

- r = read
- w = write
- x = execute
- "-" = no access
#### first character in line:
- d = directory
- "-" = file
    - permissions  
    - rwx   r-x   ---
    - user group other
