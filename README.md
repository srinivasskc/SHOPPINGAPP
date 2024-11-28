
# Shopping App
This is a sample project to learn Python project structure.

## Project Structure:

```
shoppingapp/
├── .gitignore
├── configs/
├── ├── index.py
├── ├── settings.yaml
├── LICENSE.md
├── README.md
├── requirements/
├── ├── requirements.in
├── ├── requirements.txt
├── setup.py
├── src/
├── ├── main.py
├── ├── utils/
├── ├── ├── helper.py
├── ├── ├── __init__.py
├── ├── __init__.py
├── tests/
├── ├── test_main.py
├── ├── __init__.py
```

##  Instructions

1. Create a folder or directory - ShoppingApp
2. Initialize the git: git init -b main
3. Add ReadMe.MD File  with some information
4. Add Folder Structure

configs: --> settings.yaml

src -> utils -> __init__.py, helper.py

src -> source code ->> main.py

tests -> __init__.py, test_main.py

venv -> virtualenvironment

setup.py -> python setup

LICENSE.md -> License details

README.md -> ReadMe details file.

Install dependencies  
requirements.in -> 
requirements.txt


## License  

[MIT](https://choosealicense.com/licenses/mit/)


## .gitignore file:

 __pycache__ : This folder directory is created automatically when a python script is created which has import module added.
 This __pycache__ folder contains .pyc file ie. compile python file.
Since these are automatically created, it is often ignored in version control systems.


*.egg-info/

.env

.credentials


