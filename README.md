# VSC Java project using Gradle

This is an example of a Java project for Visual Studio Code.
It uses a Gradle organize the build and classpath.
You will need the "Java Extension Pack" in VSC.  
Obviously, you'll also need to install Java and set up the JAVA_HOME environment variable.

A nice feature here is that VSC generates the dot-files for Eclipse.

## How to create a VSC project for Maven

1. In the VSC terminal:
   1. Move to the desired parent directory, create your project directory, and then move into the project directory.
   2. Use gradle to create the project:  `gradle init --type java-application`
   3. You will now have a sample project, with a main class named `App`
2. In VSC, use File > Open... to open the new project folder.
3. Modify the existing Java files.  Change `App` to whatever you need.
4. Modify the `build.gradle` file to contain your actual dependencies.
5. The gradle project will automically recompile every time you start it in the debugger.
5. Do File > Save Workspace as... to create a workspace file inside the project folder.

