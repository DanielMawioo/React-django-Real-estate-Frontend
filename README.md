# Django-React Real Estate App
## This is a large project that shows how to implement a real estate application with a variety of different features:
- 1. Authentication using JSON Web Tokens with the Django Rest Framework Simple JWT package. 
- 2. A contact form.
- 3. A pagination. 
- 4. Uploading photos on the Django Admin, 
- 5. custom the Django Admin.
- 6. Redux signals

In order to test out this project, follow these steps:
- clone the repository
- run: npm install, this will install the required frontend packages
- run: npm run build, this will make the production react build folder
- run: python3 -m venv venv
- then activate the virtual environment
- run: pip install -r requirements.txt
- in realest_estate/settings.py, under DATABASES, set the PASSWORD field to your database password
- in realest_estate/settings.py, under EMAIL_HOST_USER, set your email that you are using
- in realest_estate/settings.py, under EMAIL_HOST_PASSWORD, set your app password you are using
- in contacts/views.py, under the send_mail function, input the email you are using