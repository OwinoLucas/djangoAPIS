# DRF APIs
## Description
Django Rest endpoint boiler plate project with user application wrapped with JWT authentication and a blog application with a POST endpoint to work with.

## Postman Screenshots
### registration endpoint
![Screenshot from 2023-07-28 13-31-52](https://github.com/OwinoLucas/djangoAPIS/assets/60548928/ec8031c1-5971-4d0b-9c63-0623e3810591)
### Login endpoint
![Screenshot from 2023-07-28 13-32-02](https://github.com/OwinoLucas/djangoAPIS/assets/60548928/7ac9fd69-d8da-4c42-bf11-b775de7fc931)
### Post blog endpoint
![Screenshot from 2023-07-28 13-32-16](https://github.com/OwinoLucas/djangoAPIS/assets/60548928/1e198846-d77e-44b2-826d-29adfe9ca83c)


##### Cloning the repository:

```bash
https://github.com/OwinoLucas/djangoAPIS.git                                       
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