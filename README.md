# taskbuster-setup
A simple script to setup a Project template for Django based on  taskbuster-boilerplate.
See github page at  https://github.com/mineta/taskbuster-boilerplate  for taskbuster-boilerplate. 


# Usage 

```sh 
./tbsetup.sh  project_name env_prefix python_path  pip_command 

project_name   : Name of Django Project to create. 
env_prefix     : The prefix to be used for virtualenv names . 
                 Environment will be created like  preifx_dev, prefix_test etc. 
python_path    : Path to python intepretter, eg. /usr/bin/python3 
pip_command    : pip or pip3  

```
Example 
```sh
./tbsetup.sh  myDjango  myd  /usr/bin/python3  pip3  

This will clone taskbuster-boilerplate to ../ , setup virtualenvs
myd_test, myd_dev .  All project references will be changed to myDjango. 

```

# Links  
Taskbuster-Boilerplate  : https://github.com/mineta/taskbuster-boilerplate 
Taskbuster Django Tutorial Marina Mele : http://www.marinamele.com/taskbuster-django-tutorial 

