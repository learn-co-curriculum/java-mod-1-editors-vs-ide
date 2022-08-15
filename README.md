# Editors vs. IDEs

## Learning Goals

- Explain the differences between text editors, code editors, and IDEs

## Introduction

You can create a Java program with any text editor and then compile and run that
program with the JDK. However, as you start spending more and more time writing
code, you will quickly realize that many tasks are repetitive and that, not
unlike many other professions, specialized tools can not only help with these
repetitive tasks, but can also allow you to do things that wouldn't otherwise be
possible.

There are 3 types of tools with which you can write code:

1. Text editor.
2. Code editor.
3. Integrated Development Environment (IDE).

## Text editor

As you know, source code is text, so technically any text editor can be used to
create any source code, including in Java. And since Java provides command-line
based tools to compile and run its code, you can use those directly on the
command line and never use anything else.

There are severe limitations with this approach, however, starting with the fact
that any time you want to compile your code to find out if it has any errors in
it, you need to switch between your text editor and your command line to run
your compiler.

## Code Editor

A code editor is a specialized text editor that has many features specifically
targeted at developers, including:

1. The ability to see all the files in your project at once and organize them
   from within the editor.
2. Syntax highlight, making it easier to see the difference between variables,
   hardcoded values, methods, and parameters.
3. Syntax validation, which highlights syntax errors in real-time while you're
   typing your code - no need to wait until you compile your code to see your
   potential errors.
4. Ability to compile and run your code from within the code editor.
5. Integration with source code management tools, such as GitHub.

Some code editors also offer plugins to support additional functionality for
specific languages. Microsoft Visual Studio Code is a free code editor, and
offers coding pack for Java, which is also free:
<https://code.visualstudio.com/docs/languages/java>.

The advantages of a Code Editor over a text editor are obvious. The advantages
over an IDE are more subjective, as code editors like VS Code can be customized
to be almost as powerful as IDEs (which we'll discuss next) and do have the
advantage of being cheaper (or free), more customizable and lighter weight. They
can, however, take more work to configure properly and can almost never be
configured to support 100% of the features that a mature full-fledged IDE
supports.

## IDE

An IDE usually has most or all the features of a code editor and then adds the
following types of features:

1. Generally dedicated to a specific language (like Java), but have support for
   additional languages which are common usually (such as Javascript, HTML and
   CSS).
2. Supports all the features of that language.
3. Full-featured integration with source code management tools, such as GitHub.
4. Full-featured integration with build tools, such as Maven or Gradle.
5. Integrated debugger, which allows us to step through each line of code as the
   JVM executes it.
6. Support for additional tools, such as diagramming and UI design.

One of the most popular IDEs for Java is IntelliJ. It will support everything
you need today, is very easy to get up and running (because it's dedicated to
Java) and has many features that make the life of a Java developer easier.
