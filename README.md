# running-tests
An Executable  JAR which when included in any project , execute the methods defined in the properties file.

Description : 
This project is a plugin which is initially meant for running test classes methods in android. (PART OF THE JAVA DEVELOPMENT on ANDROID)
This executable jar can be used with any IDE(AIDE,Terminal IDE,etc) for android or for desktop env which supports JAVA and can be considered as a plugin which can be included in any project as an external library.

Pre-requisites:
*  The TestIt.properties file must be defined in the classpath. 
           - In eclipse (or any desktop IDE), This can be defined in the root of the project whose test class needs to be executed.
           - In android IDEs , the properties file must be defined in the root directory of the android file system i.e., "/" .

*  The methods and its class name must be defined in TestIt.properties file in the following way :
             class_name = method_name1,method_name2,method_nameN
