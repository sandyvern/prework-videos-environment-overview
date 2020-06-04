# Environment Overview

## Learning Goals

+ Explain what a development environment is and what it is used for
+ Describe the purpose of the Learn IDE
+ Use the Learn IDE to solve a lab

## Lesson

<iframe width="100%" height="720" src="https://www.youtube.com/embed/-5Iz6JnsUzM?rel=0&showinfo=0" frameborder="0" allowfullscreen></iframe>

+ Hi guys, it's Ian from Flatiron School. In this video, we're going to learn about development environments. Our Learning Goals for this video are:
+ To explain what a development environment is and what it is used for
+ To describe the purpose of the Learn IDE
+ And to use the Learn IDE to solve a lab
+ Before we dive in, there's one thing that's important to remember when you're programming.
+ That is that all code is just text in a file that can be understood by a computer.
+ So any file, with instructions in it that a computer can understand, that's code.
+ Our job, as programmers, is to create those files. We want to create files that  a computer can interpret as instructions.
+ The set of tools that software developers like you and me use to create and modify those code files is called a development environment
+ At the bare minimum, this includes two things:
  + A text editor, to edit those text files containing the code.
  + A way to execute, or run the code that you've written.
+ There are many different text editors that you could use. If you wanted to, you could write all of your code in Microsoft Word or a Notepad.
+ It's easier, though, to use a text editor that's specifically designed for code. Some popular text editors for code are Sublime Text, Atom, VSCode. There are a whole bunch of other ones.
+ These give you helpful things such as syntax highlighting and autocompletion.
+ Once you've edited the code, you need a way to execute it. For an HTML page, this might be as simple as opening it in a web browser. Let me go ahead and open up my text editor, which is Atom, and create a new file called `index.html` - I can quickly add some HTML in here.
+ When I open this in the web browser, I'll see the output from that code.
+ So that works really well for things like HTML, but for other applications, you'll likely need to execute the code from a terminal. For example, when writing a Ruby application, I need some way to be able to execute that ruby code.
+ We can do this using the Ruby interpreter - this is a tool that runs from the terminal to execute our Ruby code. If I make a new file, let's call this one 'app.rb' and put a simple print statement here, we can now run this code from my Terminal using `ruby FILENAME` - so in this case, `ruby app.rb`
+ We now see the output of that program.
+ So, I'm doing this on my Mac, and one thing to note is that setting up a development environment on your computer can be a little bit of a pain.
+ I have to make sure that I have Ruby installed, plus maybe other libraries depending on what I'm doing or working on.
+ To make things easier to get started, we at Flatiron School created a tool called the Learn IDE.
  + IDE stands for "Integrated Development Environment" - this is a one stop shop that includes all of the tools, libraries, and packages that you need to be able to develop an application.
+ The Learn IDE is replicating what would happen if you had the same development environment on your computer.
+ When you see a new lab in Learn, you can use the "Open in IDE" button to launch the Learn IDE.
+ I'll go ahead and do that now on this lab.
+ You'll see two pieces here - the text editor and the terminal. I can write code using the text editor here, and execute it in the terminal.
+ So if I want to test something out that I wrote, I can make a new file called `app.rb` and invoke it using `ruby app.rb` - just like I did before.
+ Once I've solved the lab, I can run the `learn` command to execute the test suite. Learn will automatically recognize the changes.
+ Later on in your programming journey, you'll want to set up a local environment on your computer to make it easier to work on large-scale projects.
+ For now, though, the Learn IDE will help you get up and running quickly.
+ So to recap, in this video we discussed what a development environment is and why we use them.
+ We talked about why we built the Learn IDE - to make it faster to get solving lessons and labs on Learn.
+ And we looked at solving a lab using the Learn IDE.
+ Thanks so much for watching, and happy coding!
