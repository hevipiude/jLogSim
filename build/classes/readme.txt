javac -Xlint:unchecked -Xlint:deprecation logsim/*.java
jar -cf logsim.jar logsim/*.class
java -cp logsim.jar logsim.LogSimApp

classpath????