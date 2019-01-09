# Compilers
Some tutorials for COMP 520 Compilers

# Setting up the environment

## for 64-bit windows users
you can download the portable version [eclipseJDK-win-x86_64.zip](https://github.com/qzane/Compilers/releases/download/20190109/eclipseJDK-win-x86_64.zip), unzip it, and run the eclipse.exe.

## for ubuntu users
### install jdk and eclipse
```
sudo apt-add-repository ppa:mmk2410/eclipse-ide-java
sudo apt-get update
sudo apt-get install openjdk-8-jdk
sudo apt install eclipse-ide-java
```
### import the examples
1. Download the [Archive Files](http://www.cs.unc.edu/~prins/Classes/520/)
2. Open Eclipse IDE, go to the workbench and create a Java project (say simpleScannerParser).
3. Under simpleScannerParser, right click the "scr" icon , and select "import..."
4. The import source should be "General -> Archive File"

# FAQ
## Why there is nothing happened when I press the "run" button?
Try "windows" -> "Show View" -> Console, when you see the console, enter some expressions like 1+2, and hopefully you will see the output.
