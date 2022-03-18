py -3 -m venv venv# Corona Archine

Corona Archive is an application which aims to track Corona Infections via contact tracing. We aim to do this by registering people when they enter a business in collaboration with business owners, marking people as infected in collaboration with hospitals, and contacting people who are likely to have infection with the help of our admins. 


## Table of content
1. [Features](#f)
2. [Built with](#bw)
3. [Getting started](#gs)
4. [Implementation](#i)
5. [Authors](#a)
6. [Future updates](#fu)

## <a name="f">Features</a>
- Registration for **visitors** and **business owners**
- Login for **visitors**, **business owners**, **hospitals**, and **agents**
- **Agents** can add **hospitals**


## <a name="bw">Built with</a>
* HTML
* Javascript
* CSS
* Python

## <a name="gs">Getting Started</a>
To run this application, you need to follow the following steps.\
First of all, you need to have python3 nd pip installed. You can find python installation guide [here](https://www.python.org/downloads/) and pip installation guide [here](https://pip.pypa.io/en/stable/installation/). \
Once python and pip are installed, there are various python modules that are also required. \
Before we can install these modules, we need to create a virtual environment to run Flask. Follow the steps [here](https://flask.palletsprojects.com/en/2.0.x/installation/) to create a virtual environment in our application's working directory.\
Once the terminal with the virtual environment in our application's working directory is ready, enter the following commands to install the required packages.\
```pip install flask```\
```pip install flask-sqlalchemy```\
```pip install flask-wtf```\
```pip install flask-bcrypt```\
```pip install flask-login```\
```pip install email_validator```\
Once all the packages are installed, run the following command in the same command line.\
```python run.py```\
Then, open http://127.0.0.1:5000/ in your web browser to view our application.

## <a name="i">Implementation</a>
### Sprint 1
We implemented the frontend of our application using HTML, Javascript, and CSS. No external frameworks or libraries were used in this application. The backend was implemented using Flask.

## <a name="a">Authors</a>
1. Sprint 1
    * Abhishek Ojha
    * Suraj Giri

## <a name="fu">Future updates</a>
- [x] Generate a QR code for business owners
- Scan QR code to enter a business
- Hospitals can mark users as infected
