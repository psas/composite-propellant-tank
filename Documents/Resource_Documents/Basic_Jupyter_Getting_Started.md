***Getting Started with Jupyter Notebooks***

**Installing Jupyter Notebook:**

1.  Download Anaconda software package which includes Python 3, Jupyter notebook, and a host of other useful analysis tools: [*https://docs.continuum.io/anaconda/install*](https://docs.continuum.io/anaconda/install)

2.  Follow these instructions if you get stuck: [*https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook\#gs.null*](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook#gs.null)

3.  When you have it installed, you should be able to type *‘jupyter notebook*’ into command prompt, and have it open up a new window in your browser showing the directory of your active jupyter notebooks, this will likely be ‘Documents’ or another high-level user folder.

4.  Remember: when you close the browser window, that does not shut down the Jupyter kernel. To properly shut down Jupyter notebooks, go back to the command window and hit *Ctl + c* to end the session.

Jupyter notebook only has one working directory at a time, so you want to make sure that it opens up to our team’s active notebook directory, which leads me to…

**Changing/Assigning your Jupyter Notebook Directory (Windows):**

1.  If you haven’t done so already, install Gitbash and clone the PSAS/Composite Fuel Tank project directory to a desired location on your computer (make sure it is where you want it semi-permanently).

2.  Create a jupyter configuration file by entering the following into command terminal: *‘ jupyter notebook --generate-config’* This will create a configuration file in the ‘~/.jupyter’ folder on your computer. This will probably be right in your user directory.

3.  Navigate to this folder and open up the configuration file you created. You will probably want to open this with a basic text editor such as notepad.

4.  Scroll down until you find the following line:(~ line 179)

*\#c.NotebookApp.notebook\_dir = u'...current directory'*

1.  Uncomment the line by removing ‘\#’ and insert our team’s active notebook directory (~\\*composite-propellant-tank\\Analysis\\Calculations'*) where the current directory is. This will vary slightly depending upon where you put your git clone folder.

ex. My directory looks like this:

*c.NotebookApp.notebook\_dir = u'OneDrive\\CompositeTank\_Docs\\composite-propellant-tank\\Analysis\\Calculations'*

Now, save the file and restart Jupyter notebook. It should now open to this directory.

**Editing and Viewing Jupyter Notebooks:**

The browser window allows for creation and direct editing of jupyter notebooks. For basic usage- writing text and playing around with variables- this is fine; if you are interested in anything more complex, I recommend an external IED such as Pycharm, which has built-in support for Jupyter Notebooks and Git.

If you want to create a jupyter notebook for a given analysis, but are running into roadblocks, feel free to fill in an outline with needed equations and explanations. Someone with more programming experience can go in later and develop the notebook. Additionally, any additional documents (.csv data files or images) that the notebook might need should be clearly labeled and in the same folder as the notebook.

**Github Integration:**

Very Important!

Make sure you are working on the most current version of a notebook by checking for updates via gitbash.

In order for your changes or contributions to be registered, remember to push to github after every editing session.

Easiest way to do both these things:

Right click on your local \\*composite-propellant-tank* folder in windows explorer and select “Git Bash Here”. Now you are in the right directory to pull, commit, push, etc.

Jupyter Quickstart Guide: [*https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/*](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/)
