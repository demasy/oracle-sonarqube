# Understanding SonarQube for Oracle SQL & PL/SQL
This is my experiment to gain a better understanding of SonarQube as a code analyzer for PL/SQL and Oracle SQL code.

<br>

## Installation
- Download the <a href="https://www.sonarsource.com/products/sonarqube/downloads">SonarQube</a>
- Download Java JDK Development Kit 17.0.7 <a href="https://www.oracle.com/java/technologies/downloads/#java17">Java JDK 17.0.7</a>

<br>

##### set SONAR_JAVA_PATH 
```shell
setx SONAR_JAVA_PATH "C:\Program Files\Java\jdk-17\bin\java.exe"
```

##### Set Java Command 
```shell
set wrapper.java.command=C:\Program Files\Java\jdk-17\bin wrapper.java.command=C:\Program Files\Java\jdk-17\bin\java
```

##### Install Sonar Service
```shell
<SonarQube-Home>\bin\windows-x86-64\SonarService.bat install
```

##### Start Sonar Service
```shell
<SonarQube-Home>\bin\windows-x86-64\SonarService.bat start
```

##### Check Sonar Service Status
```shell
<SonarQube-Home>\bin\windows-x86-64\SonarService.bat status
```
