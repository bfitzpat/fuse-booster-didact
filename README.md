# fuse-booster-didact

Provides a Devfile to do the following:
- import the console-java-sample project
- install the Didact extension
- install the Java extension
- provide two build tasks

Next steps:
- create a Didact file that walks the user through running the project
    * execute the build and run task
- then explain how to change the file so it shows a different message
    * open the java file to the right line
    * explain what to change it to
    * execute the build and run task
- set the didact file as the default and pop it up at startup

Follow-on steps:
- provide a way to put the Didact file in a separate column at startup so it doesn't collide with other open files
- provide a way to put the java file at the right line (I think this exists already but need to check)
