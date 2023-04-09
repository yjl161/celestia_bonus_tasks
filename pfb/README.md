This is a simple example app built with pywebio and Flask. 

## Prerequisites
You need to have the following software installed on your machine:
 - Docker

## Running the application
To run the application, clone this repository to your local machine and navigate to the project directory. Then, start the application using `docker`.
```
git clone https://github.com/LUNA007KING/celestia_bonus_tasks.git
cd celestia_bonus_tasks/
cd pfb/
docker build -t flask-app .
docker run -p 5000:5000 flask-app
```
This will start the frontend and backend services in separate containers.
You will be able to access the application at http://localhost:80. 
The backend service will be running on http://localhost:5000, and the frontend service will proxy requests to the backend service automatically.

Demo: http://89.58.48.29:5000/
