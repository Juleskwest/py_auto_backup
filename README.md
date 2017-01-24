# py_auto_backup
python script to auto back up a python project or any other files that older versions are wanted.

eg working on a python script, and each day you are done or just want to save what you have you can run it and it will back up all the files you want it to file tree.

eg:
  file_to_save.txt
  
  it will then save this in:
  
  V0/V0/V1
  
  then the next time you run the script it will save the next in:
  
  V0/V0/V2
  
  for now you have to manually update the 1st or 2nd version numbers

Usage:
  You need to have a file called file_list.txt
  
  with the format:
  
  \<0.0.1>
  file_to_save.txt
  
  then you run the python script and it will backup the files and add one to the version number eg now its \<0.0.2>
  
  
