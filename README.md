# TodoApp
<p align='center'>  
  <img src="https://i.imgur.com/hIWbNXU.png">  
</p>

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![made-with-django](https://img.shields.io/badge/Made%20with-django-156741.svg)](https://www.djangoproject.com/)
[![maintenance](https://img.shields.io/badge/Maintenance%20intended-Maybe-orange.svg)]()
[![Contributions](https://img.shields.io/badge/Contributions-Open-green.svg)](https://github.com/IlyasDiker/TodoApp/pulls)

## Description
Just a simple ToDo app using django (Creat, Read, Update, Delete)


## Models
Task Model
```php
class Task(models.Model):
    title = models.CharField(max_length=200)
    complete = models.BooleanField(default=False)
    created = models.DateTimeField(auto_now_add=True)
```

## Requirements
- Django 3.1.3
- Python 3.9