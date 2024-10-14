# VNP-2024-25

The file [requirements.txt](requirements.txt) contains the required Python packages you need to install to be able to run the notebooks. 

THE REQUIREMENTS WILL BE UPDATED AS WE LEARN MORE PACKAGES, MAKE SURE TO CHECK AND INSTALL ANYTHING THAT YOU'RE MISSING.

It's recommended to use Anaconda (Miniconda) to manage the packages and to easily access Jupyter Notebook.

## Optional - Create a Virtual Environment

### Option 1

#### Create virtual environment - Anaconda interface
Create a virtual environment. Virtual environments help you separate the version of Python and the packages you use for each project. If you don't create a virtual environment, the package versions and the Python version are global for your entire system.

#### Install packages
In Anaconda you can create a virtual environment by clicking the '+' sign in the Environments tab. Give the environment a name, and search for the packages from the [requirements.txt](requirements.txt) file to install them by clicking on the '+' sign.

### Option 2
You can create an environment using Python's virtual environment module in the following way:

```
python3 -m venv <name_or_path_to_environment>
```

In order to use the virtual environment, you need to activate it (for this example let's set the name of the environment to 'venv'):


#### Linux or Mac
```
source venv/bin/activate
```

#### Windows
```
venv\Scripts\activate.bat
```

#### Install packages
To install all of the packages run this command after activating the virtual environment:

```
pip install -r requirements.txt
```

