helloworld-windows: Basic Windows Mobile Hello World App
========================================================
Author: Erik Jan de Wit (edewit)
Level: Beginner  
Technologies: Windows Phone
Summary: A basic example of the Platform : Send your name and get a Hello <name> response
Target Product: Mobile  
Product Versions: MP 1.0   
Source: https://github.com/feedhenry-templates/helloworld-windows

What is it?
-----------

This project is a very simple helloworld, to show how to send something to the platform and have get a response ("Hello <name>")

System requirements
-------------------

Visual Studio 2015 or 2013

Build and Install
-----------------

Open the HelloWorld Visual Studio project and build

Build and Deploy the HelloWorld
-------------------------------

## Change fhconfig.json 

fhconfig.json will be automaticly filled if build / created from the platform if you use this manually you'll have to update the configuration

Application Flow
----------------

Fill in a name and push "Say Hello" to send it to the [cloud app](https://github.com/feedhenry-templates/helloworld-cloud) see the response appear below the button.