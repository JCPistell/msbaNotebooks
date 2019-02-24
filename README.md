MSBA Notebooks
-------

A collection of notebooks used during Extra Sessions for the CU Boulder's MSBA program.

## Running the Notebooks

*Prerequisites:*
- Python
- Git
- either Docker (preferred) or a locally running version of jupyter

Clone this repo. For the purposes of the following examples let's assume you've cloned it to `~/Projects/msbaNotebooks`

For Docker:

1. If you need to install Docker you can find instructions [here](https://www.docker.com/get-started)
2. execute the following command: `docker run -p 8888:8888 -v ~/Projects/msbaNotebooks: /home/jovyan --rm jupyter/base-notebook` (be sure to include your correct location)
3. If this is the first time you've run this command you'll need to wait for Docker to pull down the relevant images
4. When everything has launched open a browser and navigate to localhost:8888

### Windows & Docker:
At last check Windows had trouble running both Docker and Virtualbox/VMWare at the same time, which is incredibly stupid and annoying. There are workarounds that you can google but Windows users may find it easier to just run Jupyter locally.

## Running Jupyter Locally:

It's less clean but will definitely work

1. Install Jupyter. See notes [here](https://jupyter.org/install)
  - If you've already installed python with Anaconda then you already have Jupyter
  - Otherwise, follow the relevant instructions.
  - I'd suggest using [virtualenvs](https://realpython.com/python-virtual-environments-a-primer/) if at all possible. 
2. Navigate to the directory you cloned the notebooks into (e.g. `~/Projects/msbaNotebooks`)
3. Start a notebook server with `jupyter notebook`

## If all else fails

You can get a rendered (but non-interactive) version of the notebooks [here](https://nbviewer.jupyter.org/github/JCPistell/msbaNotebooks/tree/rendered_results/)
