#### Setup 
Clone the project:
- ```cd Full\ Stack\ Cloud\ Dev\ Capstone\ Project/server```
Install the required Python packages
- ```python -m pip install -r requirements.txt```

Create a [new Django Secret Key](https://humberto.io/blog/tldr-generate-django-secret-key/) 

Run the development server: </br>
```
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

Create a new superuser:

```
python manage.py createsuperuser
```

> Log in via the admin site (just add `/admin` at the end of the url)

Push to IBM Cloud Foundry:
- Install the IBM Cloud CLI and the cloud foundry plugin
- Configure the `manifest.yml` file


```
ìbmcloud cf push
```


