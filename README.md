# py-dev

Just osme notebooks and supporting infrastructure for a quick look at pythn

## Installation

To use this code, you need of python3 and the [pipenv](https://pypi.org/project/pipenv/) package manager to install these notebooks.

In a [Terminal](https://www.businessinsider.com/how-to-open-terminal-on-mac) window verify python3 is installed by tyoing in this command:
`python3 --version`

After thast, install the pipenv package manager, which will be used to install libraries and tools (called dependencies) for this code:
`pip install pipenv`

Next, download this code to your computer. Find a good spot, say your Documents folder to store this code:
`cd ~/Documents`

Using git, a tool that manages code store in github, we copy the code to our laptop:
`git clone https://github.com/cxplanet/py-dev`

Change directories to the py-dev code we just copied:
`cd py-dev`

Use the pipenv tool to download the libraries we need and create a new workspace to do our coding in:
`pipenv shell`

And finally, launch our notebook, so that we can do coding:
`jupyter notebook`
