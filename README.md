#  Django Rest Framework Tutorial

This is a step-by-step guide to create a rest API.
It follows the tutorial at:
[Django-rest-framework](https://www.django-rest-framework.org/)

## Create virtual environment

* create a directory called rest-api-test: 

``` 
$ mkdir rest-api-test
```
* To activate the virtual environment cd into `rest-api-test` and type:

```
$  source venv/bin/activate
```

## Installing Django

* install Django, you need to download the PIP('Preferred Installer Program') to install python packages. You can find the list of Python packages available at 'https://pypi.org/'
* To install pip the latest version of pip, run this command: "python -m pip install --upgrade pip"
* To keep our project organised, we keep our dependencies into a file. So, create a file called "requirements.txt" in our main folder(in my case django)
* Once we have created our "requirements.txt' file, we write the Django version we are going to use. For this particular project, I wrote: "Django~=3.2.10". We now save the file.
* Now we need to install the dependency that we have listed into the "requirements.txt" file or "Django~=3.2.10"
To install dependencies run this command: "pip install -r requirements.txt"

