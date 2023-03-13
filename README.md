# 0x00. AirBnB clone - The console

## Description

The goal of the project is to deploy on your server a simple copy of the AirBnB website.
It is a web application that will be integrating database storage, a backend, and  front-end interface.


## The Storage

The application data is stored and manipulated from the database called the `Storage`
Every time the backend is initialized, AirBnB instantiates an instance of 
`FileStorage` called `storage`. The `storage` object is loaded/re-loaded from 
any class instances stored in the JSON file `file.json`. As class instances are 
created, updated, or deleted, the `storage` object is used to register 
corresponding changes in the `file.json`.


## The Console

The console is a command line interpreter that allows for the management of the backend
of the AirBnB application.


