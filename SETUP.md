# Installation and setup
Some setup instructions are given below.

## Python
Make sure Python 3.8+ is installed on your system. We recommend using `pyenv` with `pyenv-virtualenv` for managing multiple versions of Python and setting up a separate virtual environment to keep things clean, but the choice of how to install virtual environments and dependencies is yours! Please make sure to include a `requirements.txt` file or similar to help reproduce your environment on other systems.

## Neo4j
The installation instructions for Neo4j and Neo4j Desktop on Mac/Ubuntu/Windows are shown on their [web page](https://neo4j.com/docs/operations-manual/current/installation/).

It is recommended to set up a virtual environment and install the required Python dependencies via a `requirements.txt` file. Using `pyenv` for Python 3.10.4, it would look as follows.

```sh
$ pyenv virtualenv 3.10.4 <your_virtual_environment_name>
$ pyenv shell <your_virtual_environment_name>
$ python -m pip install -r requirements.txt
```

For further development, simply activate the existing virtual environment.

```
$ pyenv shell <your_virtual_environment_name>
```