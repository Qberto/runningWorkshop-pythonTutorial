# Introduction

Python is a programming language that lets you work more quickly and integrate your systems more effectively. You can learn to use Python and see almost immediate gains in productivity and lower maintenance costs. (Python Software Foundation, 2019)

In GIS and many interdisciplinary fields, Python has grown in use tremendously, likely due to its ease of use, capabilities, and adoption of British humour and dad-jokes. 

Whether you are a GIS user, system administrator, data scientist, or aspiring singer, knowing at least a little bit about Python is key to your success. Let's go on this journey to tame the Python!

## What is Python?

### A Language

Python is a scripting and programming language with its own syntax, style-guide, and best practices. 

### A Program

Python is also an executable program that can run on your computer, on the cloud, or in your dreams if you've been scripting all day. At some point in your adventures you will see a Python.exe program (if on Windows). This program accepts arguments, which could be Python scripts. This program can also be installed a variety of ways, and comes in a plethora of applications. Ultimately, you need to know that in addition to writing Python code, you will also be running Python as a program.

### An Ecosystem

My favorite part of Python is the community and the overwhelming amount of functionality at your fingertips once you are acquainted with the basics. From determining the current date, to translating to any language, to performing advanced statistical analysis and data visualization, to running web servers, and everything in between those non-linear concepts: Python's got your back. Or better yet: the Python community's got your back. 

There are a tremendous amount of Python enthusiasts that are building Python tools and responding to questions on Stack Overflow. If you ever feel lonely, just give Python a try and you will soon feel the need to ask the Python community a question. Inevitably, you will land at other Python developers and people that strive to solve problems. 

## Why is Python?

Python is used successfully in thousands of real-world business applications around the world, including many large and mission critical systems. Here are some quotes from happy Python users:

"Python plays a key role in our production pipeline. Without it a project the size of Star Wars: Episode II would have been very difficult to pull off. From crowd rendering to batch processing to compositing, Python binds all things together," said Tommy Burnette, Senior Technical Director, Industrial Light & Magic.

This quote is less impressive when you actually remember Star Wars: Episode II...

## Where is Python?

Python can be installed in far too many ways. That's part of what makes it a bit confusing to get started... For example, all Macs come with Python. ArcGIS itself comes with Python, and ArcMap came with a different version of Python than ArcGIS Pro, which changed the rules for how to use it. There is also a Python executable that you can install directly from the Python Software Foundation at Python.org... but most people recommend that you install Python from a larger package, like the one from Anaconda, which includes scientific libraries. Blah blah blah blah...

Needless to say, this is part of what makes getting started a bit less straightforward than installing yelp on your phone (this workshop is not sponsored by Yelp). It's tough to know where to get started. 

To make things easy today, we'll start our exploration with the Anaconda distribution of python, which comes turbo-charged with a large amount of packages and tools that will help use Python and hit the ground running. 

In a future session, we'll explore the Python environment in ArcGIS Pro, which comes with its own quirks and whistles:
![Python in ArcGIS Pro](https://pro.arcgis.com/en/pro-app/arcpy/get-started/installing-python-for-arcgis-pro.htm)


## When is Python?

Now! Let's get started.


# Step 1: Install Python via Anaconda

For this introduction, we will leverage Anaconda, a free and open source distribution of Python that simplifies package management and deployment. One advantage of this approach is that it completely isolates any work from your important ArcGIS Pro python environment. 

## Procedure:

To install Anaconda, please use the following link: https://www.anaconda.com/distribution/#download-section

Once downloaded, run the installer and leave the following two options **unchecked**:

- Add Anavonda to my PATH environment variable
- Register Anaconda as my default Python 3.7

![Unchecked Options](https://github.com/Qberto/runningWorkshop-pythonTutorial/tree/master/media/anaconda02.PNG) 

Once installation is complete, let's run a few checks:

1. Open the Anaconda Command Prompt by selecting Start > Anaconda > Anaconda Command Prompt

![Anaconda Command Prompt](https://github.com/Qberto/cv-objectdetection-workshop-2018/blob/master/media/Capture2.PNG) 

This is very similar to the regular Windows command prompt, with a few important differences:

- Python executables point to the Anaconda installation version of python.
- A conda environment is established. 

What is a [conda environment](https://conda.io/docs/user-guide/concepts.html#conda-environments)? Well it's a way to ensure that a python installation and all the stuff we're going to pile up on top of it does not interfere with other installations of python that run important stuff for us.

From this environment, we can run Python simply by typing "python" and selecting enter.

Enter a the following:

`print("Hello World")`

Then press Enter. Congratulations, you've run Python code! 

Now marvel at how simple this is compared to the equivalent Java code to say "Hello World":

`/* This is a simple Java program. 
   FileName : "HelloWorld.java". */
class HelloWorld 
{ 
    // Your program begins with a call to main(). 
    // Prints "Hello, World" to the terminal window. 
    public static void main(String args[]) 
    { 
        System.out.println("Hello, World"); 
    } 
}`

Wow.

Exit the python command prompt by entering:

`exit()`

And pressing enter. Your command prompt should look like this:

![Anaconda Command Prompt](https://github.com/Qberto/cv-objectdetection-workshop-2018/blob/master/media/cmd01.PNG) 

2. Write and save a python script, then execute it. 

A command prompt lets us enter commands, one by one. However, that's not very conducive to scripting or automating a sequence of steps. So now let's write and save a script with a few commands that can be invoked in one call to the script. 

Open your notepad editor, then enter the following commands:

`print("Hello World")
print("My name is <Enter your name>.")
print("I am a University of Florida fan.")`

Then save the file as "my_first_script.py" inside the same path shown on the Anaconda Command Prompt. 

Now, let's execute this script by running:
`python my_first_script.py`

Your output should look like the following:

![Anaconda Command Prompt](https://github.com/Qberto/cv-objectdetection-workshop-2018/blob/master/media/cmd01.PNG) 

Congratulations! You've written and executed a Python script!

# Step 3: Install Sublime Text 3

Writing code on a notepad editor is not very helpful once we start getting into more complex work. For this reason, we'll make use of a text editor that is intended for writing code. Sublime Text 3 is a free, lightweight program intended to help you quickly author Python scripts with syntax highlighting and additional extensible tools. 

The installer can be found at: https://www.sublimetext.com/3

# Step 4: Install PyCharm

While Sublime Text 3 helps us edit Python code by highlighting syntax, there are far more comprehensive tools for authoring Python code once we get into more complex workflows. These tools are referred to as Integrated Development Environments, or IDEs for short. 

PyCharm is a very powerful IDE, and it's capabilities will take you very far without further customization. 

The installer can be found at: https://www.jetbrains.com/pycharm/download/#section=windows

That's it for now! Stay tuned for our next session.  
 