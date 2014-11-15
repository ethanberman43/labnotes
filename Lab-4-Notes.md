#Lab 4 Notes
One of the Thesises of course: View the operating system as a textual piece  

Touch - creates a blank file   
Echo - repeats what you type in screen
	ex: echo "hey guys" > test.txt  
	ex: >> doesn't remove other content, > does (DANGEROUS)  

history - shows history  
history | less shows history beginning at 1  
history, CTRL + R backsearches through history

BEST PRACTICE: do not use spaces in your files so you can easily access them in terminal AND do not use capitals, both spaces and capitals matter  
- ex: mac doesn't recognize case sensitivity, while Linux does  
- i asks for confirmation if you want to do it (cp -i target1.txt target2.txt asks for confirmation if you actually want to copt t1.txt into t2.txt and overwrite t2.txt)
- cp is copy: cp target1.txt target2.txt copies t1.txt into t2.txt  
- mv: move ex: mv target3.txt .. moves up 1 directory
- rm: removes files, but safer not to do this, instead:   
- mkdir trash and mv all files to trash, then permanently delete trash periodically  
- operating in verb averd noun
		noun is always a path  
- wget: grab something online
	

Absolute vs. Realtive Path: absolute path begins at beginning of root, relative is path from where you are

	