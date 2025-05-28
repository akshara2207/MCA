In event app ,
create a urls.py file 
   from django.urls import path 
   from . import views

urlpatterns= [ path(‘’,views.index,name=‘index’)]

In event app, views.py
From django.shortcuts import render

Create your view here.

def index(request):
          return render(request,’index.html’)

