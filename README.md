#Build Instructions

This project is tested to build on Java 8 or Java 7. 
You can download lastet version of JDK from http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html

It uses Maven as its build system, and should run on Maven 3.0 and above. 
You can download lastet version of Maven  from https://maven.apache.org/download.cgi

Git serves as our distributed revision control system.
You can find detailed information on how to install git on your system at http://git-scm.com/book/en/v2/Getting-Started-Installing-Git


##Git Checkout and Initialization

Check out the project using a normal Git clone command:

	git clone https://github.com/deart2k/RCPsample.git


###Building with Maven

Run this command inside the root directory of project:

	mvn clean install

After build will be success you will can to find bilds of product for different platforms in folder 
RCPsample\releng\com.mytest.tycho.product\target\products\

Tycho-linux.gtk.x86_64.zip 
Tycho-win32.win32.x86.zip
Tycho-linux.gtk.x86.zip
Tycho-macosx.cocoa.x86_64.zip
Tycho-win32.win32.x86_64.zip
