# Overview


This is the server side (Backend) for a car showroom displays the services offered by the showroom, and the owner of the showroom controls everything, such as what services are displayed and control the display of images for each service and control for all data shows in the site for all services and all packages. Users can also book an appointment to do a specific service and pay via their visa.


# Dependencies

- python3
- Django~=4.0.2
- djangorestframework~=3.13.1
- Pillow~=9.0.1
- jwt~=1.3.1
- stripe~=2.66.0
- PyJWT~=1.7.1
- qrcode~=7.3.1
- django-material-admin~=1.8.6
- djangorestframework-jwt~=1.11.0
- psycopg2==2.9.3
- asgiref==3.5.2

# To Use

To clone and run this repository you'll need Git and Node.js (which comes with npm) installed on your computer. From your command line

```bash
# Clone this repository
git clone https://github.com/CreativeAxisEG/EvoCare_Website_api.git
# Go into the repository
cd EvoCare_Website_api
#Create virtual environment 
python -m venv env
#activate virtual environment on linux
.env/bin/activate
#activate virtual environment on Windows
.env/Script/activate
#inistal all requirements
pip install -r requirements.txt
#inistal all requirements
pip install -r requirements.txt
#prepare the database 
python manage.py migrate
# Run the app
python manage.py runserver
```

# Client Side 

you can see the client side (frontend) wich built using Reactjs from here
https://github.com/minaemad13/EvoCare_Website
