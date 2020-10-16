# MOVIE TICKET BOOKING
![developer](https://img.shields.io/badge/Developed%20By%20%3A-Sumit%20Kumar-red)
---
## SCREENSHOTS
### Home Page
![home snap](https://github.com/sumitkumar1503/movieticketbooking/blob/master/static/screenshot/home.png?raw=true)
### Download Ticket
![ticket snap](https://github.com/sumitkumar1503/movieticketbooking/blob/master/static/screenshot/ticket.png?raw=true)
### Admin View Movie
![admin snap](https://github.com/sumitkumar1503/movieticketbooking/blob/master/static/screenshot/admin.png?raw=true)
### Seat Choose
![seat snap](https://github.com/sumitkumar1503/movieticketbooking/blob/master/static/screenshot/seat_choose.png?raw=true)
### Theatre Collection
![theatre snap](https://github.com/sumitkumar1503/movieticketbooking/blob/master/static/screenshot/theatre.png?raw=true)
---
## FUNCTIONS

---
### Admin
- First admin will login ( for username/password run following command in cmd )
```
py manage.py createsuperuser
```
- Give username, email, password and your admin account will be created.
- After login , admin can

---
### Other Features
-
## HOW TO RUN THIS PROJECT
- Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)
- Open Terminal and Execute Following Commands :
```
pip install django==3.0.5
pip install django-widget-tweaks
pip install xhtml2pdf

```
- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands :
```
py manage.py makemigrations
py manage.py migrate
py manage.py runserver
```
- Now enter following URL in Your Browser Installed On Your Pc
```
http://127.0.0.1:8000/
```

## CHANGES REQUIRED FOR CONTACT US PAGE
- In settins.py file, You have to give your email and password
```
EMAIL_HOST_USER = 'youremail@gmail.com'
EMAIL_HOST_PASSWORD = 'your email password'
EMAIL_RECEIVING_USER = 'youremail@gmail.com'
```
- Login to gmail through host email id in your browser and open following link and turn it ON
```
https://myaccount.google.com/lesssecureapps
```
## Drawbacks/LoopHoles
-

## Disclaimer
This project is developed for demo purpose and it's not supposed to be used in real application.

## Feedback
Any suggestion and feedback is welcome. You can message me on facebook
- [Contact on Facebook](https://fb.com/sumit.luv)
- [Subscribe my Channel LazyCoder On Youtube](https://youtube.com/lazycoders)
