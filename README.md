# django-blogiee
A Django based Blog App with Progressive Web App support and Trusted Web Activity compatiable
[![logo](https://github.com/codekushi/django-blogiee/blob/master/blog/static/icons/Django-Blogiee.png?raw=true)](https://django-blogiee.herokuapp.com)

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
- custom Progressive Web App(TWA compatiable)

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

## I am working under development of transforming [PWA](https://django-blogiee.herokuapp.com) into APK using [Trusted web activity(TWA)](https://github.com/codekushi/django-blogiee/blob/deploy-twa/twa-app/app-release-signed.apk) whose code is in [deploy-twa](https://github.com/codekushi/django-blogiee/tree/deploy-twa) branch

## [deploy-twa](https://github.com/codekushi/django-blogiee/tree/deploy-twa) branch contains [deployed website](https://django-blogiee.herokuapp.com) and APK file for the deployed wesite built using Trusted Web Activity(TWA) using [Bubblewrap](https://github.com/GoogleChromeLabs/bubblewrap)

### A detailed blog post on customization is found at [Customizing Django-Blogiee](https://hackingandprogramming.com/tutorial/customize-django-blogiee)
