# Ex02 Django ORM Web Application
## Date:20-03-2025

## AIM
To develop a Django application to store and retrieve data from a Movies Database using Object Relational Mapping(ORM).

## ENTITY RELATIONSHIP DIAGRAM

![image-2](https://github.com/user-attachments/assets/81beb1fc-e11c-4adc-8fac-354c14854d81)

## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for admin.py and models.py

### STEP 4:
Execute Django admin and create details for 10 books

## PROGRAM
```
class Student(models.Model):
    user=models.CharField(max_length=100,primary_key=True)
    password=models.CharField(max_length=100)
    email=models.EmailField()
    phone=models.CharField(max_length=100)
    profile=models.ImageField(upload_to='profile/')
    address=models.TextField() 
```
## OUTPUT

![Screenshot 2025-03-19 161047](https://github.com/user-attachments/assets/39f13d8c-8545-4717-b84e-d6731b598b5b)


## RESULT
Thus the program for creating movies database using ORM hass been executed successfully
