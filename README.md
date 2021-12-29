# Rename-multiple-files
Now the requirement is to rename them in ordered fashion like hostel1, hostel2, …and so on. Doing this manually would be a tedious task but this target can be achieved using the rename() and listdir() methods in the os module.
 

The listdir method lists out all the content of a given directory.

Syntax for listdir() : 

list = os.listdir(‘src’) : where src is the source folder to be listed out.

The following code will do the job for us. It traverses through the lists of all the images in xyz folder, defines the destination (dst) and source (src) addresses, and renames using rename module. 

The accepted format for destination (dst) and source (src) addresses to be given as arguments in os.rename(src,dst) is “folder_name/file_name”.
