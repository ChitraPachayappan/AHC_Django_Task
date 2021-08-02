Django Task:
------------
Python version = Python 3.8.5
Django version = (3, 2, 4, 'final', 0)

1. Create project and application 
    Create project : django-admin startproject company
    Create app inside company dir - python3 manage.py startapp staff

2. Create Model need to migration (tables added in staff/models.py)
    python3 manage.py makemigrations
    python3 manage.py migrate
    
3. Added in admin.py 

4. python3 manage.py createsuperuser (Need to give username, email,password) 
   python3 manage.py runserver ( browse url - localhost:8000/admin/ need to enter credentials and can able to view admin page)
   
5. Department list - localhost:8000/department_list/ 
   Department Detail - localhost:8000/department/<department_id>/ 
  
6. Form created for employee

7. Create employee url - localhost:8000/create_employee/

8. templates added in staff/templates/staff/ folder.
