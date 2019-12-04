<pre>
As of 191125
. this is the way we are installing Oracle JDK on Windows 10
Using the Windows 10 go to
- Control Panel\System and Security\System
- Then click Advanced System Settings
- - Click Environmental Varaibles
- - - Add the following variable JAVA_HOME for the local user.
JAVA_HOME contains the following line of code:   
C:\Program Files\Java\jdk-13.0.1

Then add the following to your local Path to set the path.
 %JAVA_HOME%\bin 


Type java -version at terminal (Powershell)

%appdata%
%localappdata%

old notes

</pre>


