# Simple Notes App
This is a simple notes app built with React and Django.

<img width="997" height="930" alt="image" src="https://github.com/user-attachments/assets/04208050-c765-432b-b65f-cf7f46941ac1" />


## Requirements
1. Python 3.9
2. Node.js
3. React

## Installation
1. Clone the repository
```
git clone https://github.com/LondheShubham153/django-notes-app.git
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
