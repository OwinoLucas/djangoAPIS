# DRF APIs
## Description
Django Rest endpoint boiler plate project with user application wrapped with JWT authentication and a blog application with a POST endpoint to work with.

## Postman Screenshots
### registration endpoint
![image](https://{file:///home/looading/Pictures/Screenshots/Screenshot%20from%202023-07-28%2013-31-52.png
})
### Login endpoint
![image](https://{file:///home/looading/Pictures/Screenshots/Screenshot%20from%202023-07-28%2013-32-02.png
})
### Post blog endpoint
![image](https://{file:///home/looading/Pictures/Screenshots/Screenshot%20from%202023-07-28%2013-32-16.png
})

##### Cloning the repository:

```bash
https://github.com/OwinoLucas/I-Reporter.git
```

##### Navigate into the folder and install requirements

```bash
cd djangoAPIS pip install -r requirements.txt
```

##### Install and activate Virtual

```bash
- python3 -m virtualenv venv - source venv/local/bin/activate
```

##### Install Dependencies

```bash
pip install -r requirements.txt
```

##### Setup Database

SetUp your database User,Password, Host then make migrate

```bash
python manage.py makemigrations 
```

Now Migrate

```bash
python manage.py migrate
```

##### Run the application

```bash
python manage.py runserver
```

##### Testing the application

```bash
python manage.py test
```

Open the application on your browser `127.0.0.1:8000`.
## Tech Stack
* Python 3.10.1
* Django 3.2.3
* Django Rest Framework 3.12.4
* psycopg2 2.8.6
* django-cors-headers 3.2.1
## License
Copyright (c) [2023] [Lucas Otieno]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.