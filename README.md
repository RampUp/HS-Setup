Setup: High School RampUp
========

Welcome to the High School RampUp setup page. Please follow the instructions below to get your computer ready for class. 

__We ask that every student go through this setup on the laptop that they plan to bring to class.__   

If you have a choice of computers to bring, we would prefer you brought a computer running Mac OSX, as OSX is what our teachers use most often and are therefore the best at troubleshooting. However, we love Windows and Linux machines too.

If your computer runs Mac OSX
---
1. Open up your terminal. You can search for the terminal application in the Spotlight window (the magnifying glass on the upper right-hand corner of your screen.)

2. Type

	```
	python 
	```
	And press ENTER. You should see something similar to one of the following:

	```
	Python 2.7.4 (default, Apr 14 2013, 15:47:35)
	[GCC 4.2.1 Compatible Apple LLVM 4.2 (clang-425.0.27)] on darwin
	Type "help", "copyright", "credits" or "license" for more information.
	>>> 
	```
	NOTE: You may have a verison of Python that is different than 2.7.4. __That's okay__ as long as its above Python 2.3.

	Or you should get an error. If you get an error, [download Python (2.7.4 or 2.7.3) from here](http://www.python.org/getit/) and go through the installation instructions for your machience. Please be concious of if your computer needs a 32 or 64-bit install.

3. Install a text editor. We highly reccomend Sublime, which is a great free text editor for code. [To download Sublime, follow the instructions here](http://www.sublimetext.com/2). 

4. Awesome! You're all set.


If your computer runs Windows
---

1. Search for your terminal program by typing __cmd__ into the start menu and pressing ENTER.

2. Type:
	```
	python
	```
	And press ENTER. 

3. If your system recognizes python, it should return something similar to the following in the cmd window:
	```
	Python 2.6.5 (r265:79063, Mar 20 2010, 14:22:52) [MSC v.1500 32 bit (Intel)] on win32
	Type "help", "copyright", "credits" or "license" for more information.
	>>>
	```

	Otherwise, if it does not recognize Python, it should return:
	```
	python is not recognized
	```
	
	In this case, [install Python from 2.7 from here](http://python.org/download)

4. Open powershell (you can do this by searching for powershell in the Start menu) and type:
	```
	python
	```

	If it still returns an error enter: 
	```
	 [Environment]::SetEnvironmentVariable("Path", "$env:Path;C:\Python27", "User")
	```

	And close powershell and open it. Try typing 
	```
	python
	```
	And see if it works (i.e. has >>>). If it does not, try restarting your computer. If not, [email us.](mailto:juliana@startupinstitute.com)

5. Awesome! You're all set.

Credits + Contact Info
---
If you have any trouble with these install instructions, please [contact us.](mailto:juliana@startupinstitute.com)
Thanks to [Learn Python the Hard Way](http://learnpythonthehardway.org/book/ex0.html) and [The Hitchhiker's Guide to Python](https://python-guide.readthedocs.org/en/latest/) for help with install instructions.