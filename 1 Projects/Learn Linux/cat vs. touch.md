cat comes from "concatenation": cat file1 file 2 file3 > file 4
It can be used to both display files and also create a file
--> To display file, just use "cat" followed by file name
	It can take options.: show line number, show EOL, show Tabs, etc
--> To change a file (create, overwrite append, etc), the redirection utility of the shell is used.
	It can be used to redirect the standard output to a file 
	overwrite ==> "cat > file name"
	append ==> "cat >> file name"
--> If used to create a new file ("cat > file") and write data to the new file (whatever is typed on    the console shall be redirected to the newly created file and Return key  follwed by Ctrl + D is used to both save the file and exit cat
It can be used to create only one file at a time


Touch is used to create a new empty file
Touch can create several new files at once
If the file already exists, then touch simply updates the timestamp
