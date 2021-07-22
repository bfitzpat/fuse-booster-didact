# So You Want to Send a Custom Message

We all know that "Hello, World" is one of the oldest forms of communication when it comes to learning how to write a computer program, but let's stick with it for a moment.

Here we have a simple Maven-backed Java program that will write out `Hello World [some string]!` to the console. 

### Running the Code As-is

If you look at the `HelloWorld.java` code in the project ([see `console-java-simple/src/main/java/org/eclipse/che/examples/HelloWorld.java`](didact://?commandId=vscode.open&projectFilePath=/projects/console-java-simple/src/main/java/org/eclipse/che/examples/HelloWorld.java)), you can see a simple `System.out.println` that takes in a string and outputs our message to the console.

To see it in action, you can run it as a task by clicking the `Terminal->Run Task` menu and select `maven build and run` option. After the project builds, you should see `Hello World Che!` appear in the `maven build and run` terminal window at the bottom. (Click [here](didact://?commandId=workbench.action.tasks.runTask&text=maven%20build%20and%20run) to automatically run the task.)

### Changing the Message

To change the message output to the console, all we have to do is modify the string added as part of the message. Let's look at `HelloWorld.java` one more time and look at changing that string ([see `console-java-simple/src/main/java/org/eclipse/che/examples/HelloWorld.java`](didact://?commandId=vscode.open&projectFilePath=/projects/console-java-simple/src/main/java/org/eclipse/che/examples/HelloWorld.java)). 

Change the string on line 9 of `HelloWorld.java`.

Thomas Note: Eventually we will be able to go directly to the correct line with a different Didact command but that Didact version is not yet in the Che plugin registry. The didact command would be:`didact://?commandId=vscode.didact.openUriWithLineAndOrColumn&projectFilePath=/projects/console-java-simple/src/main/java/org/eclipse/che/examples/HelloWorld.java&text=9` to open the same file we opened before but move the cursor automatically to line 9.

Change that to `from Me` and then run the `maven build and run` task one more time. (Click [here](didact://?commandId=workbench.action.tasks.runTask&text=maven%20build%20and%20run) to automatically run the task.)

You should see `Hello World from Me!` show up in the terminal window this time.
