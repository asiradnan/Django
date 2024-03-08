# Django
```bash 
sudo apt install python3-pip
``` 
```bash
sudo apt install python3-django
```
```bash 
django startproject MedicalService
```
## Connecting mysql
```bash
sudo apt-get install python3-dev default-libmysqlclient-dev build-essential pkg-config
```
```bash
pip install mysqlclient
```
<pre>DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'MedicalService',
        'HOST': '127.0.0.1',
        'PORT': '3306',
        'USER': 'root',
        'PASSWORD': ''
    }
}</pre>
