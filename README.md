# django-blogiee
A Django based Blog App with Progressive Web App Support

![logo](https://github.com/codekushi/django-blogiee/blob/master/blog/static/icons/Django-Blogiee.png?raw=true)

## Dependencies used
- django
- django-summernote
- django-otp
- django-admin-honeypot

You can deploy the app in any hosting service that supports Django. You can use my [Digitalocean referral link](https://m.do.co/c/7d066b069429) and get $100 credit for 60 days

## App features
- Integrated with Django Summernote Editor
- Django Admin security with Django Admin Honeypot and Django OTP
- Responsive Web pages with Dark Mode
- custom Progressive Web App
- Custom Admin Dashboard

### Instructions to use
- Install Python3
- clone the Repo
```
git clone https://github.com/codekushi/django-blogiee.git
```
- install Dependencies
```
pip install -r requirements.txt
```
- run the following commands
```
python manage.py makemigrations
python manage.py makemigrations blog
python manage.py migrate
python manage.py runserver
```
## Now you can see the home page by going to 127.0.0.1:8000

### A detailed blog post on customization is found at [Customizing Django-Blogiee](https://hackingandprogramming.com/tutorial/customize-django-blogiee)
