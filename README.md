# Jupyter!

### What is it?
It’s an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and explanatory text. The application can be executed on a PC/MAC without internet access or it can be installed on a remote server, where you can access it through the internet. 

Jupyter has two main components: The Kernel and Dashboard.

The Kernel is a program that runs and introspects the user’s code. The Jupyter Notebook App has a kernel for Python code, but there are also other kernels available for other programming languages.

The Dashboard of the application not only shows you the notebook documents that you have made and can reopen but can also be used to manage the kernels: you can see which ones are running and shut them down if necessary.

### History of Jupyter

Python - Late 1980s - Guido Van Rossum begins to work on Python at the National Research Insitute(NRI) for Mathematics and Computer Science in the Netherlands.

IPython - Late 2001 - Fernando Perez starts developing IPython. Which, ended up becoming the name of the Python backend and a kernel for Jupyter.

Jupyter - 2014 - Fernando Perez announced a spin-off project from IPython called Project Jupyter. 

### How to install Jupyter for us experienced Python users. 
-Run the following command in the Terminal 
pip3 install jupyter

### Setup
In the Terminal, type in:
Jupyter notebook

Once you have the server up and running, look for the text that says
“Copy/paste this URL into your browser when you connect for the first time,
    to login with a token:
        http://localhost:8888/?token=6bad7be1f33b54c62e3e6b997a90eb5c6c93046e2cc134a4”
Follow those instructions.

### Demo
Run the following command to open up the application:

`jupyter notebook`

Then you'll see the application opening in the web browser on the following address: http://localhost:8888. 

![](http://community.datacamp.com.s3.amazonaws.com/community/production/ckeditor_assets/pictures/191/content_jupyternotebook1.gif)

<<Insert DataCamp Gif>>
The "Files" tab is where all your files are kept, the "Running" tab keeps track of all your processes and the third tab, "Clusters", is provided by IPython parallel, IPython's parallel computing framework. It allows you to control many individual engines, which are an extended version of the IPython kernel.

We will start by creating a “New Notebook.”
We will do simply do this by clicking on the “New Button” in the “Files” tab.


If you want to get the most out of your notebooks with the IPython kernel, you should consider learning about the so-called "magic commands". 

The Notebook's Built-In Commands
There are some predefined ‘magic functions’ that will make your work a lot more interactive.
To see which magic commands you have available in your interpreter, you can simply run the following:
`%lsmagic`
Tip: the regular Python help() function also still works and you can use the magic command %quickref to show a quick reference sheet for IPython.





Resources

http://jupyter.org/index.html
Jupyter on GitHub
https://github.com/jupyter/help
Jupyter on StackOverflow
https://stackoverflow.com/questions/tagged/jupyter





