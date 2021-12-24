# Maven
1. Apache Maven is a java based software project management and comprehension tool. Based on the concept of a project object model (POM). 
2. Maven can manage a project's build, reporting and documentation from a central piece of information. 
3. Maven provides d a complete build lifecycle framework for project management. 
4. Development team can automate the project's build infrastructure in almost no time as Maven uses a standard directory layout and a default build lifecycle.
5. In abstract, Maven simplifies and standardizes the project build process. 
6. It handles compilation, distribution, documentation, team collaboration and other tasks seamlessly. Maven increases reusability and takes care of most of build related tasks.

# Build Process
The ”Build” is a process that covers all the steps required to create a deliverable product of your software into preproduction and production. In the Java world, this typically includes: 
1. Generating source.
2. Compiling sources.
3. Executing tests (unit tests, integration tests, etc). Packaging (into jar, war, ejb-jar, ear).
4. Running health checks (static analyzers like Checkstyle, Findbugs, PMD, test coverage, etc). Generating reports.

A defined build process is an essential part of any development cycle because it helps close the gap between the development, integration, test, and production environments. A build process alone will speed the migration of software from one environment to another. It also removes many issues related to compilation, classpath, or properties that cost many projects time and money.

# 6.	Uses of Apache Maven
1. Use as Build Tool
2. Use as to manage Project structure
3. Building, publishing and deploying
4. Documentation
5. Reporting
6. Releases
7. Distribution

# Download Maven
```
https://maven.apache.org/download.cgi
# Select the appropriate zip or tar file depending on your local OS.
```

# Installing Apache Maven
1. unzip apache-maven-3.8.4-bin.zip
2. tar xzvf apache-maven-3.8.4-bin.tar.gz

# Windows Tips
```
echo %JAVA_HOME% 
C:\Program Files\Java\jdk1.7.0_51
```
_Adding to PATH: Add the unpacked distribution's bin directory to your user PATH environment variable by opening up the system properties (WinKey + Pause), selecting the “Advanced” tab, and the “Environment Variables” button, then adding or selecting the PATH variable in the user variables with the value C:\Program Files\apache-maven-3.8.4\bin. The same dialog can be used to set JAVA_HOME to the location of your JDK, e.g. C:\Program Files\Java\jdk1.7.0_51_

_Open a new command prompt (Winkey + R then type cmd) and run mvn -v to verify the installation._


# Unix-based Operating System
```
echo $JAVA_HOME
/Library/Java/JavaVirtualMachines/jdk1.8.0_45.jdk/Contents/Home
export PATH=/opt/apache-maven-3.8.4/bin:$PATH
```

# Running Apache Maven
```
mvn -h
```

# First Sample Application
```
# Download all maven plugins
mvn archetype:generate

# Choose a number, we are choosing 981 for org.apache.maven.archetypes:maven-archetype-quickstart version

Define value for property 'groupId': sampleapp
Define value for property 'artifactId': sampleapp
Define value for property 'version' 1.0-SNAPSHOT: : 
Define value for property 'package' sampleapp: : 
Confirm properties configuration:
groupId: sampleapp
artifactId: sampleapp
version: 1.0-SNAPSHOT
package: sampleapp
 Y: : Y
 
```




