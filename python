# import json library

import json

info_about_me = {
    "name": "Michele",
    "has_a_dog": False
}

# save dictionary

with open("info.json", "w") as f:
    json.dump(info_about_me, f)
    
    
# make a statement

import json

with open("info.json", "r") as f:
    info = json.load(f)

if info["has_a_dog"]:
    print("{} has a dog".format(info["name"]))
else:
    print("{} does not have a dog".format(info["name"]))
    
    
# python django view function

from django.shortcuts import render
from django.http import HttpResponse

def members
(request):
    return HttpResponse("Hello world!")
    
# send a variable

from django.http import HttpResponse
from django.template import loader

def members(request):
  template = loader.get_template('mytemplate.html')
  context = 
{

    
'points': 5
,
  
}

  return HttpResponse(template.render(context, request))
  
  
 # list of paths to handle requests
 
 from django.contrib import admin
from django.urls import include, path

urlpatterns
 = [
    path('', include('members.urls')),
    path('admin/', admin.site.urls),
]

# use models

from django.db import models

class Member
(models.Model):
  firstname = models.CharField(
max_length=100
)

# migration due to changes handling

py manage.py 
makemigrations
 members


py manage.py 
migrate

# specify field

from django.db import models

class Test(models.Model):
  points = models.
IntegerField
()

# write new variable

<h1>Hello 
{{
 firstname 
}}
, how are you?</h1>

# simple if statement


{%
 if greeting == 1 
%}

  <h1>Hello</h1>
{%
 
endif
 
%}


# django queryset

Member.objects.
filter
(
firstname='Tobias'
).values()

# filter names with 'L'

Member.objects.filter(
firstname__startswith='L'
).values()

# descending sorting

Member.objects.all().
order_by('-firstname')
.values()

# hosting on any domain name

# SECURITY WARNING: don't run with debug turned on in production!
DEBUG = False

ALLOWED_HOSTS = ['*']

# collecting static files


STATIC_ROOT
 = BASE_DIR / 'productionfiles'

STATIC_URL = 'static/'
