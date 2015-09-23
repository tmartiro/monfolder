## monfolder

This version is monitor mount point for a new file creation. The program supports recursive monitoring of file creation. When file is created the program executes specified script which was passed itself as an argument. 

It uses linux kernel  fanotify API for monitoring events. [http://man7.org/linux/man-pages/man7/fanotify.7.html]

### how to compile
- clone repo 
- change dir to "monfolder" 
- invoke
  ``make``
  
## usage
monfolder \<mount_folder\> \<script_to_execute\>

## example
``monfolder /var/www /home/tmartiro/sync.sh``
