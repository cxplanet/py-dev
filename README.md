# py-dev

Just some notebooks and supporting infrastructure for a quick look at python

## Installation

To use this code, you need of python3 and the [pipenv](https://pypi.org/project/pipenv/) package manager to install these notebooks.

In a [Terminal](https://www.businessinsider.com/how-to-open-terminal-on-mac) window verify python3 is installed by tyoing in this command:
`python3 --version`

After that, install the pipenv package manager, which will be used to install libraries and tools (called dependencies) for this code:
`pip install pipenv`

Next, download this code to your computer. Find a good spot, say your Documents folder to store this code:
`cd ~/Documents`

Using git, a tool that manages code store in github, we copy the code to our laptop:
`git clone https://github.com/cxplanet/py-dev`

Change directories to the py-dev code we just copied:
`cd py-dev`

Use the pipenv tool to download the libraries we need - this
will likely take a while:
`pipenv install`

After installing the libraries we need, we start a 'shell', basically a workspace to run our notebook in:
`pipenv shell` You should see a prompt change to something like `(py-dev) bash-3.2$ `

And finally, launch our notebook, so that we can do coding:
`jupyter notebook` Once launched a web browser should apper - you can click on the notebooks to run them

You can shut down the notebooks by finding the terminal window and typig a Ctrl-C, ie holding down the control key and press the letter 'C' on the keyboard at the same time, and then pressing the 'Y' key when prompted
