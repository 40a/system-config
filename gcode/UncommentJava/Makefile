all:
	java org.antlr.Tool Java.g
	javac *.java
	jar cfv ~/bin/Linux/ext/`uname -m`/uncomment-java.jar *.class

clean:
	git clean -fxd
