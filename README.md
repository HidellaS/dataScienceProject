# This is an end to end data science project

### 1 - first step is to create and environment for this project
This is important because. each an every project has it's own seperate dependancies (packages, modules etc.) it even can have different python versions. some may use python 3.10 some may use 3.12 etc. so by haveing individual environemnt for each project we can segragete the project and can avoid future clashes.

`conda create -p venv python=3.12 -y`

`conda activate venv/`

### 2 - Second step is to create a requirments.txt file for the project
This is important because. in here we put all the packages we want to do the project. if we were to manual install every pacakge in the terminal by typing pip install xxxx it will take forever and it will be a teadeous task. there for buy typing all the pacakge names in the text file and just installing the text file is much easier

`pip install -r requirements.txt`

### 3 - Third step is to create a template.py file
in this file we specifiy the folder strucute and automate it to crate using pythong scrips

`python template.py`

we use setup.py file so we can convert the entire project to a package. (we can do things like put them into pypi)