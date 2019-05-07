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