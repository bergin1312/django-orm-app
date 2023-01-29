# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## DESIGN STEPS

### STEP 1:
Clonining of repository.Setting up of admin models

### STEP 2:
To make all migrations in the app.Test the server.

### STEP 3:
Include the detials in the tables.


## PROGRAM
```
from django.db import models
from django.contrib import admin
class Employee(models.Model):
    emp_id=models.CharField(primary_key=True,max_length=4,help_text="Employee ID")
    ename=models.CharField(max_length=50)
    post=models.CharField(max_length=50)
    salary=models.IntegerField()
    age=models.IntegerField()
    email=models.EmailField()

class EmployeeAdmin(admin.ModelAdmin):
    list_display=('emp_id','ename','post','salary','age','email')  
```


## OUTPUT

![Screenshot from 2023-01-30 00-46-37](https://user-images.githubusercontent.com/119404594/215350438-2ce5552a-8ce2-4e80-9c15-59f7af705ba0.png)


![Screenshot from 2023-01-30 00-47-16](https://user-images.githubusercontent.com/119404594/215350466-216a1fc2-a8ac-4362-a5e9-b82948866a20.png)



## RESULT
Thus we delveloped a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).
