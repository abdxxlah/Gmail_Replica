# Gmail_Replica
Created a replica of a GMail web app using Python and Javascript and fit into Django, Bootsrap, and VSCode

Gmail Replica
This is an email client that I named Gmail Replica. The system makes API calls to send and receive emails built using Django 4, HTML 5, CSS 3, Bootstrap 5 and fundamental JavaScript.



Prerequisites
Install the following prerequisites:
Visual Studio Code
Python 3.8-3.11
On Visual Studio Code, go to extensions and install and enable the “Python” extension, once in the code terminal.
Django 


Installation
1. Create a virtual environment
After downloading the code onto VSCode, go to File -> Terminal -> New Terminal
From the root directory run:
python -m venv venv
2. Activate the virtual environment
From the root directory run:
On macOS:
source venv/bin/activate
On Windows:
venv\scripts\activate
3. Install required dependencies
From the root directory run:
pip install -r requirements.txt
4. Run migrations
From the root directory run:
python manage.py makemigrations
python manage.py migrate
Run the application
From the root directory run:
python manage.py runserver
View the application
Go to http://127.0.0.1:8000/ to view the application.
Note
Just remember to send an email to an email address that already exists in this GMAIL Replica database.
Copyright and License
Copyright © 2022 Abdullah Muhammad. Code released by MIT license and allowed public.


