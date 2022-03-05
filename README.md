# Basic web app tutorial

This repository has a very basic example of backend and frontend communication. The backend is written in Python using the Flask framework and the frontend is HTML with plain JavaScript.

This project is explain on my Blog at: [Python backend with JavaScript frontend: how to](https://tms-dev-blog.com/python-backend-with-javascript-frontend-how-to/)

## Set up

Install the requirements for the backend by first creating a virtual environment in the backend directory:

```
cd backend
python -m venv venv
```
Then install the dependencies:

```
pip install flask flask-cors
```

## Running the project

Start the backend server using the following command:

```
python app.py
```

Start the frontend using [http-server](https://www.npmjs.com/package/http-server):

```
http-server
```

Navigate using a browser to the address the frontend is hosted at. This is `http://localhost:8080` by default.
