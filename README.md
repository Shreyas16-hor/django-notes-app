# Simple Notes App for TWS Community
This is a simple notes app built with React and Django.

## Requirements
1. Python 3.9
2. Node.js
3. React

## Installation
1. Clone the repository
```
git clone https://github.com/Shreyas16-hor/django-notes-app.git
```

2. Build the app
```
docker build -t notes-app .
```

3. Run the app
```
docker run -d -p 8000:8000 notes-app:latest
```

## Nginx

Install Nginx reverse proxy to make this application available

`sudo apt-get update`
`sudo apt install nginx`

![image alt](https://github.com/Shreyas16-hor/django-notes-app/blob/c5ab421b57fd58319861020bc77d236745e6c0bd/Screenshot%202025-02-06%20105553.png")
