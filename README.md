## Create a root of any directory

A simple bash script that instantiates a .root file in your application's parent directory so you don't have to type `cd ..` all day long.

##Instructions
1. `git clone `  
2. Create an alias in your .bashrc file pointing to `root` and calling source or `.` 
(ex. `. alias="path/to/root"`) 
3. Call `root create` on the parent directory of your application
4. Whenever you are within the subdirectories, call `root` and return to your parent!

That's it!
