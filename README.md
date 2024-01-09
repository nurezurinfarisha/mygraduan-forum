----This folder DOESNT contain virtual environment folder--

1)To create virtual environtment , use
  $python -m venv <virtual_environment_name>
  $<virtual_environment_name>\Scripts\activate
  
2)after the creation complete, install all module requirement in the virtual environment
MAKE SURE INSTALL IN (<virtual_environment_name>).
  $pip install -r requirement.txt
  
3)check django version using
  $django-admin --version
  
4)THEN, migrate the folder
  $python manage.py makemigrations
  $python manage.py migrate
  
5)THEN, run server
  $python manage.py runserver
  
6)open the ip adress given to run the website

----END OF README---
