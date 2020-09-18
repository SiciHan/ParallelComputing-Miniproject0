## Compile using mvn Compile

$ mvn Compile

## Compile manually
$ javac -cp ./hamcrest-core-1.3.jar:./junit-4.12.jar:./pcdp-core-0.0.4-SNAPSHOT.jar:target/classes/:target/test-classes/ src/main/java/edu/coursera/parallel/Setup.java src/test/java/edu/coursera/parallel/SetupTest.java

Maven projects can be tested from the command line by simply using the following comma
$ mvn test


Testing Manually from the Command Line

$ java -cp ./hamcrest-core-1.3.jar:./junit-4.12.jar:./pcdp-core-0.0.4-SNAPSHOT.jar:target/classes/:target/test-classes/ org.junit.runner.JUnitCore edu.coursera.parallel.SetupTest

only uploading the provided source code file:

miniproject_0/src/main/java/edu/coursera/parallel/Setup.java

