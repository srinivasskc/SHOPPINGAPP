
# Shopping App
This is a sample project to learn Python project structure.

## Project Structure:

```
shoppingapp/
├── .gitignore                         # Git Ignore File
├── configs/
├── ├── index.py             
├── ├── settings.yaml                   # Settings File
├── LICENSE.md                          # Project License File
├── README.md                           # Project Readme File
├── requirements/                       # Dependencies for the Project
├── ├── requirements.in
├── ├── requirements.txt
├── setup.py                            # Python Folder Structure Generator Code.
├── src/
├── ├── main.py                         # Main Code.
├── ├── utils/
├── ├── ├── helper.py
├── ├── ├── __init__.py                 # Initialization file for configs.
├── ├── __init__.py                     # Initialization file for source code.
├── tests/
├── ├── test_main.py                    # Test Code.
├── ├── __init__.py                     # Initialization file for tests.
```


## License  

[MIT](https://choosealicense.com/licenses/mit/)


## .gitignore file:
```sh
 __pycache__ : This folder directory is created automatically when a python script is created which has import module added.
 This __pycache__ folder contains .pyc file ie. compile python file.
Since these are automatically created, it is often ignored in version control systems.

*.egg-info/
.env
.credentials
```


