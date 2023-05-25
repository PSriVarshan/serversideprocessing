# Design a Website for Server Side Processing

## AIM:
To design a website to perform mathematical calculations in server side.

## DESIGN STEPS:

### Step 1:



### Step 2:



### Step 3:



### Step 4:



### Step 5:



### Step 6:

Publish the website in the given URL.

## PROGRAM :

### urls.py
```py

from django.contrib import admin
from django.urls import path
from myapp import views


urlpatterns = [
    path('admin/', admin.site.urls),
    path('areaofrectangle/',views.rectarea,name="areaofrectangle"),
    path('',views.rectarea,name="areaofrectangleroot")
]

```

## OUTPUT:

### Server

![image](https://github.com/PSriVarshan/serversideprocessing/assets/114944059/98ebc29b-ab30-47ad-8c40-16b593e99cf6)


### Home Page:

![image](https://github.com/PSriVarshan/serversideprocessing/assets/114944059/ddb03cd7-c5b9-4978-9645-2244ccd3e11f)

### Calculated Output :

![image](https://github.com/PSriVarshan/serversideprocessing/assets/114944059/1739f8f7-f237-44f6-995c-e3e1a7cb2475)


## Result:

The program is executed succesfully
