# bash-scripts
Bash Scripting

Normal flow of Operations on computer

	[User]<----->[Terminal]<----->[Shells]<----->[OS]<----->[Hardware]
	
	We have a lot of shells there for our use
	Bourne Shell
	CShell
	Bourne Again Shell (Bash)
	Korne Shell
	etc.
	
	Shell Informations
	
	$ cat /etc/shells
	
	This will be most probable output
	
	# /etc/shells: valid login shells
	/bin/sh
	/bin/bash
	/usr/bin/bash
	/bin/rbash
	/usr/bin/rbash
	/bin/dash
	/usr/bin/dash
	
Simple Bash Script	Save it with .sh extension
This script just prints hello world
Run this via 
 $ bash name.sh

	#### Include this one first line
	
	#! /bin/bash	# The scipt you are writing for
	echo "Hello World"
	
	
