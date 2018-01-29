  
# Softwares Required
  For installation, there are 2 options: VirtualBox or Native Installation.
  
  * **Virtual Box**
  
    This provides a contained "sandbox" environment within your default OS itself to mess about. This method would help to reduce the risk of accidentally messing up your OS as the programs required for B.A.S.I.C. are isolated from your OS.
    If you're going this way, download and install VirtualBox from https://www.virtualbox.org/ And if required, enable Intel Virtualization from your BIOS. That's it!
    The rest of the steps (like loading the OS, installing softwares, etc) are to be completed by us, so rest easy.
 
 
 * **Native Installation:**
  
    If you're confident enough in working directly on your system OS, feel free to natively install the necessary software given below. These software are for the programming part. For the robotics part, we'll be switching to an IDE. Links to that would be provided when we reach that stage.
    
    Starting-out:
    1. Compiler (JDK, MinGW, Python, etc)
    2. Text Editors (Notepad, Atom, etc)
    
    Instructions and links to the software are given below according to the OS
    
    
### Installation - Linux

Installing on Linux is the easiest as you just need to type out in the Terminal

*Text Editor:*

You can use either the in-built ```gedit``` or install Atom.
If you're going with atom:
1. Open a terminal (Ctrl+Alt+T)
2. Type:
     ```sudo add-apt-repository ppa:ubuntu-desktop/ubuntu-make
     sudo apt-get update```
3. After that, run:
     ```umake ide atom```
     
If you prefer anything else, like Sublime Text or so, feel free to use those.

*Compiler:*

* If you're going with C/C++, the compilers (gcc/gpp) are already pre-installed.

* If you're proceeding in Java, choose OracleJDK over OpenJDK. 
   ```sudo add-apt-repository ppa:webupd8team/java
   sudo apt-get update
   sudo apt-get install oracle-java8-installer
   ```
   
 And follow the instructions given on-screen by the installer.

* If you're proceeding with Python, there is not much to do as they are usually pre-installed.


### Installation - Windows

EXECUTE! Just run the .exe file...

*Text Editor:*

You can use either the classic Notepad or install more powerful ones like [Atom](https://atom.io/) or [Notepad++](https://notepad-plus-plus.org/)

*Compiler:*
  
Here, it gets tricky.
* For C/C++, we'll install [MinGW](http://www.mingw.org) to get the compilers.
* For Java, we'll install [JDK8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
* For Python, we'll install Python 2.7 / 3.x from [python.org](https://www.python.org/downloads/)

After installing all these, the exe files should be added to your PATH variable automatically. If not, get in touch with any of us.

### Installation - Mac

Similar to Windows, download the MacOS files (usually .dmg files) and run them.

Unfortunately, since none of us have much experience on MacOS, Google would be your best friend.

