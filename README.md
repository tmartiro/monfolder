## monfolder

This version is monitor mount point for a new file creation. The program figures out even if file is created in subdirectories (recursive way). When file is created it executes specified script which was passed as an argument to binary. 

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
