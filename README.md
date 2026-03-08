# Task 14 – CloudKicker Deployment

## Overview
- This project demonstrates deploying a Flask web application on an AWS EC2 instance using Nginx as a reverse proxy.

## PUBLIC IP : http://13.53.130.191

## Architecture
Internet
   |
   v
Nginx (Port 80)
   |
   v
Flask (127.0.0.1:5000)

Flask is bound to 127.0.0.1:5000 and is not exposed publicly.
Nginx is running on port 80 and acts as a reverse proxy forwarding requests to the Flask application.

## Technologies Used
-  Python
-  Flask
-  Nginx
-  AWS EC2
-  Kali Linux

 
