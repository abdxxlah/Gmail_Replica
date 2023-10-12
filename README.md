# Gmail Replica

This is an email client that I named Gmail Replica. The system makes API calls to send and receive emails built using **Django 4**, **HTML 5**, **CSS 3**, **Bootstrap 5** and **JavaScript**.



![plot](https://github.com/abdxxlah/Gmail_Replica/blob/main/static/images/Gmail_Replica_SS.png?raw=true)
![plot](https://github.com/abdxxlah/Gmail_Replica/blob/main/static/images/Gmail_2.png?raw=true) 
![plot](https://github.com/abdxxlah/Gmail_Replica/blob/main/static/images/Gmail_3.png?raw=true) 



### Prerequisites

Install the following prerequisites:

1. [Visual Studio Code](https://code.visualstudio.com/download)
<br> On Visual Studio Code, go to extensions and install and enable the “Python” extension, once in the code terminal. </br>
3. [Python 3.8-3.11](https://www.python.org/downloads/)
4. [Django](https://django.readthedocs.io/en/stable/faq/install.html)



### Installation

#### 1. Create a virtual environment

After downloading the code onto VSCode, go to File -> Terminal -> New Terminal
<br></br>
From the **root** directory run:

```bash
python -m venv venv
```

#### 2. Activate the virtual environment

From the **root** directory run:

On macOS:

```bash
source venv/bin/activate
```

On Windows:

```bash
venv\scripts\activate
```

#### 3. Install required dependencies

From the **root** directory run:

```bash
pip install -r requirements.txt
```

#### 4. Run migrations

From the **root** directory run:

```bash
python manage.py makemigrations
```
```bash
python manage.py migrate
```

### Run the application

From the **root** directory run:

```bash
python manage.py runserver
```

### View the application

Go to http://127.0.0.1:8000/ to view the application.


### Copyright and License

Copyright © 2022 Abdullah Muhammad. Code released under the MIT license.
