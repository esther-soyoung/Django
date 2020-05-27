# Creating basic blog with Django
Based on [Django Girls Tutorial](https://tutorial.djangogirls.org/en/).
  
## Django
is a Python based web app framework, easing and accelerating web development by providing a set of commonly used components.
  
## Django Structure
[](img/mtv.png)
  
Django consists of three major parts: Model, Template, and View.  
* Model  
a set of tools to work with data and databases.
* Template  
a plain-text templating system.
* View  
a presentation of the Model in a particular format: HTTP.
  
That is, *Django Model* retrieves data from database, pass them to *View*, then the *View* formats the data in HTTP response and send it to the client(browser), which is templated by the *Template*.
  
## Django Project Structure
```python
pip install Django~=2.2.4
```
would yield 
- manage.py
- mysite/
    - \_\_init\_\_.py
    - settings.py
    - urls.py
    - asgi.py
    - wsgi.py
Then
```python
python manage.py migrate
```
would create a database for the app, default set to `sqlite3`.
```python
python manage.py runserver
```
would run the server.
  
### Reference
[The Django Book](https://djangobook.com/mdj2-django-structure/)
