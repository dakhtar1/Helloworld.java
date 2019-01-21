# Project 0
In this project, you will download software that allows you to run Git and submit a simple Java program to demonstrate that you have a development environment. If you do that, you will receive full credit. This assignment is weighted at 5% of your overall project grade for this course.

## Step 0 - Create a github account.
Go to the <a href="https://github.com/">website</a> and create a github account. They have <a href="https://education.github.com/pack">student packs</a> that give you access to many things that would otherwise be very expensive, so I recommend you sign up using your american.edu email address. You can associate a github account with multiple email addresses.

## Step 1 - Get git.
1. Visit the Git <a href="https://git-scm.com/downloads">website</a> and download the latest Git release for your operating system.
1. Install it, using default settings.
1. As a reference for how to use git, I suggest <a href='http://codingdomain.com/git/'>this site</a>, as it avoids some of the more complicated theory behind git and focuses on the bare minimum practicalities.

## Step 2 - Download and install the most recent JDK SE (11.0.1 or higher)
1. Go to the <a href="https://www.oracle.com/technetwork/java/javase/downloads/jdk11-downloads-5066655.html">Oracle site</a> and download the JDK SE installer for your OS.
1. Install it without
1. Here's the tricky part. You need to make Java visible to your command line tool. This is called "adding to path," and affects which commands you can run. Think about it this way - it would be pretty annoying if every time you wanted to open a Word document, you had to move that document into the same folder as Word. There is some chance that the installer did this for you, depending on your setup, but likely not. You can verify if java is available by opening your command line tool (Terminal on Mac or Powershell on PC) and typing `javac` from anywhere (yes, with a 'c' on the end). If the command is recognized, you are in good shape. If not, then you need to add it to the path.
1. Adding Java This process is different depending on your operating system. Directions for both types of systems can be found at <a href='https://www.java.com/en/download/help/path.xml'>this link</a>.

## Step 3 - Download and install a development tool
As we discussed in class, you should download and install a powerful text editor. An IDE will make it easier to perform many coding tasks, but they are more complex applications and it will be more challenging to become familiar with all of the features. There is also a risk that developing all your code in an IDE may make it more challenging to learn the details of writing code on your own - many automated processes that will not be available during quizzes and test.

#### Text Editor
*Pros:* Simple to set up and use, typically extensible, can use the same environment to develop scripts, applications, websites, academic papers, etc.

*Cons:* Very little is automated unless you extend the capabilities of the system through installed add-ons (e.g., building code, linters).

I suggest either one of the following:

1. Sublime Text 3 (recommended) https://www.sublimetext.com/
1. Notepad++ https://notepad-plus-plus.org/
1. Visual Studio Code https://code.visualstudio.com/
1. Atom https://ide.atom.io/

#### IDE

I do not recommend using an IDE for this course. In the past, the additional complexity has caused more harm than benefits.

*Pros:* Simplifies development by automating common tasks, highlighting potential errors before you try to build, and has features for building and debugging.

*Cons:* Big, complicated application with many features that we will not use in this class. Hides certain features of the development process that make it difficult to understand what is going on. Will not be available during quizzes, exams, or professional coding interviews in the hiring process.

Examples:

1. Eclipse https://www.eclipse.org/downloads/packages/installer
1. Netbeans https://netbeans.org
1. IntelliJ IDEA https://www.jetbrains.com/idea/

## Step 3.5 - Install a Linter into Sublime

## Step 4 - Clone your

## Step 4.5 - Modify the Starter Code
1. You should see a simple - but definitely broken - Java program.
1. Correct the error in the program using your text editor.
1. Compile the code using javac. (for help on how to do this, see https://introcs.cs.princeton.edu/java/15inout/windows-cmd.html)
1. Verify that the program executes.

## Step 5 - Update your local repo and push to Github
1. You will need to become familiar with a very common cycle of
1. Commit the changes to your local git repository.
1. Push the changes to the remote git repository.