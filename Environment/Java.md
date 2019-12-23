Java SE Development Kit 8u25 on a 64-bit Windows 8

Set the following user environment variables (== environment variables of type user variables)

JAVA_HOME : C:\Program Files\Java\jdk1.8.0_25
JDK_HOME : %JAVA_HOME%
JRE_HOME : %JAVA_HOME%\jre
CLASSPATH : .;%JAVA_HOME%\lib;%JAVA_HOME%\jre\lib
PATH : your-unique-entries;%JAVA_HOME%\bin (make sure that the longish your-unique-entries does not contain any other references to another Java installation folder.
Notice that all these environment variables are derived from the "root" environment variable JAVA_HOME. This makes it easy to update your environment variables when updating the JDK. Just point JAVA_HOME to the fresh installation.

There is a blogpost explaining the rationale behind all these environment variables. http://gedankenverlust.blogspot.co.il/2012/05/java-environment-variables-definitive.html
