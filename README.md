## monfolder

This version is monitor specified folder  for a new file or folder creation. When folder or file is created it executes specified script which was passed as an argument to binary.

### how to compile
- clone repo 
- change dir to "monfolder" 
- invoke
  ``make``
  
## usage

monfolder \<monitor_folder\> \<script_to_execute\>

## example
``monfolder /var/www /home/tmartiro/sync.sh``
