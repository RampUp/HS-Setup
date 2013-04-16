Setup: High School RampUp
========

Welcome to the High School RampUp setup page. Please follow the instructions below to get your computer ready for class. 

__We ask that every student go through this setup on the laptop that they plan to bring to class.__   

If you have a choice of computers, we would prefer you brought a computer running Mac OSX, as OSX is what our teachers use most often and are therefore the best at troubleshooting.

If your computer runs Mac OSX
---
1. [Click here to download XCode.](https://developer.apple.com/xcode/ "Download XCode") Xcode is Apple’s development environment. You need it installed before you can install anything else. It comes with tools used to [compile](http://en.wikipedia.org/wiki/Compiler) programs from [source](http://en.wikipedia.org/wiki/Source_code).

2. Install XCode command line tools. These are code [compiling](http://en.wikipedia.org/wiki/Compiler) tools that you can access from the [command line](http://en.wikipedia.org/wiki/Command-line_interface).   
 * Open up XCode from your applications folder 
 * Go to the toolbar: Click Preferences → Downloads → Check install command line tools    

3. Install [homebrew](http://mxcl.github.io/homebrew/), a install utility for Mac OSX, by pasting this command into the command prompt and pressing Enter. (Don't be alarmed, this will take a bit to run.)

	```
	ruby -e "$(curl -fsSL https://raw.github.com/mxcl/homebrew/go)"
	```

4. Insert the Homebrew directory at the top of your PATH environment variable by typing into your terminal the following two commands and pressing Enter after each one:

	```
	echo "export PATH=/usr/local/bin:$PATH" >> ~/.bash_profile
	source ~/.bash_profile
	brew doctor
	```

 At the end of these three commands, your terminals should say `your system raring to brew`

5. Install Python 2.7 using Homebrew by pasting this command into the command prompt and pressing Enter.
	
	```
	brew install python --framework
	```

6. Add Python 2.7 to your PATH
	
	```
	echo "export PATH=/usr/local/share/python:$PATH" >> ~/.bash_profile
	```
	
7. Download the Sublime 2 text editor. It can be [downloaded for free here](http://www.sublimetext.com/2).

8. Once you download Sublime 2, install its command line tools by entering the following command in the command prompt and pressing Enter:

	```
	ln -s /Applications/Sublime\ Text\ 2.app/Contents/SharedSupport/bin/subl /usr/local/bin/subl
	```


If your computer runs Windows
---

1. Download [Python 2.7 (click here)](http://www.python.org/getit/) and run the .exe (be sure to download the 64 or 32-bit version depending on your system)
* When you are done installing Python, open up the command prompt (Start → Programs → Accessories → Command Prompt)
* Your command prompt should look like `C:\Users\YourName>`
* Type `python` into the command prompt and press Enter
* You should see something like this:  

```python
Python 2.7.3 (default, Apr 10 2012, 22.71:26) [MSC v.1500 32 bit (Intel)] on win32
Type "help", "copyright", "credits" or "license" for more information.
```
If you do not see this, please do not worry. We will help you edit your computer's development PATH when you get to class.   

2. Download a text editor. We highly recommend (and would prefer you have) Sublime 2, which can be [downloaded for free here](http://www.sublimetext.com/2).

All set!
---
Awesome, you are all set! We will see you in class. Please be on the lookout for more updates from us.   
Email [Juliana@startupinstitute.com](mailto:juliana@startupinstitute.com) if you have any questions.