# openJDK
openJDK 7 32bit for Windows

# Install openJDK on Windows Server: 

Extract jdk_ri-7u75-b13-windows-i586-18_dec_2014.zip file into C:\Program Files (x86)\Java\ and it will create a java-se-7u75-ri folder. 

# Set a PATH: 

Select Control Panel and then System. 

Click Advanced system settings and then Environment Variables. 

Edit System variables for Path, add new C:\Program Files (x86)\Java\java-se-7u75-ri\bin 


# Set JAVA_HOME: 

Again, under System Variables, click New. 

Enter the variable name as JAVA_HOME. 

Enter the variable value as C:\Program Files (x86)\Java\java-se-7u75-r3 

Click OK all the way out to apply changes 

Test install, open up the Command Prompt and type java -version  

C:>java.exe -version 

openjdk version "1.7.0_75" 

OpenJDK Runtime Environment (build 1.7.0_75-b13) 

OpenJDK Client VM (build 24.75-b04, mixed mode) 

---------------------------------------------------------------------------------- 

Add Windows registry keys:     

Right click this file and choose merge 

This set will insert the necessary keys without having to manually add one at a time. 
