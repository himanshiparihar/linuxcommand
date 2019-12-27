# linuxcommand
1. First install `remmina` for screen viewing, by:
	1. sudo apt-get install remmina remmina-plugin-*

2. Go to search bar on top right icon and search:
	1. remmina and open it
	2. Once it is open, click on the new.
	3. First change protocol to: VNC- Virtual Network Computing 
	3. In server put : 192.168.43.230
	4. In User name put : udit
	5. Password : usp@0030
	6. Click on `Show remote cursor` and then click connect.

3. Linux commands:
	1. Linux/Ubuntu commands:
		1. ls – directory listing
		2. ls -al – formatted listing with hidden files
		3. cd dir - change directory to dir
		4. cd – change to home
		5. pwd – show current directory
		6. mkdir dir – create a directory dir
		7. rm file – delete file
		8. rm -r dir – delete directory dir
		9. rm -f file – force remove file
		10. rm -rf dir – force remove directory dir *
		11. cp file1 file2 – copy file1 to file2
		12. cp -r dir1 dir2 – copy dir1 to dir2; create dir2 if it doesn't exist
		13. mv file1 file2 – rename or move file1 to file2 if file2 is an existing directory, moves file1 into directory file2
		14. touch file – create or update file
		15. cat file.txt – shows contents of file on terminal
		16. head file – output the first 10 lines of file
		17. tail file – output the last 10 lines of file
		18. clear - clears the terminal
		
	2. Shortcut:
		1. Ctrl+c – halts the current command
		2. Ctrl+r – type to bring up a recent command
		3. Ctrl+l - clears the terminal
		4. Ctrl+shift+c - copy
		5. Ctrl+shift+v - paste
		6. sudo apt update
		7. sudo apt-get install -f

	3. Further commands: https://gist.github.com/riipandi/3097780

	4. Installing/Removing softwares:
		1. Update the softwares:
			1. sudo apt update
		2. Install package:
			1. sudo apt install <package_name>
			2. eg. : sudo apt install <htop>
		3. Remove packages:
			1. sudo apt remove <package_name>

4. Python basics:
	1. Python input and output
	2. list, tuples, dicts, class, sorting
	3. loops - for and while
	5. Numpy - Python matrix library
	6. Further reference - http://cs231n.github.io/python-numpy-tutorial/

5. Installing via python package manager : pip
	1. pip install <package_name>

6. Useful softwares:
	1. synaptic
	2. terminator
	3. htop

7. Git commands:
	1. Sign up for github.
	2. git clone <url>


8. Demo
	. -> Current directory
	.. -> Previous directory
	/home/udit == ~
	command <option> <argument>
	subl <file.txt>
	root = master = higher priveleged commands = sudo
	apt install = binaries = which can lauch from terminal

9. Demo python
	if __name__ == '__main__':		# boiler plate
	Class:
		Data variable should be define with self.
		First argument should always be self in function
