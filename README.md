# A React and Cloud Based Social Network Web Application

Designed and implemented features for users to create and browse posts; features also support the searching of the posts via keywords and users.



## Description

* Utilized React Router package to realize the redirecting and switching between various functionalities, such as “home”, “log-in”,  register”, etc.
* Adopted Axios to execute HTTP Requests, e.g., handling requests and responses for image/video uploading. 
* Adopted react-grid-gallery to realize the image selection and enlargement function for detail highlighting. 
* Improved the authentication using JWT token-based registration/login/logout flow with React Router v4.
* Launched a scalable web service in Go to handle posts; deployed the application to Google Cloud (Google App Engine).



## About the Backend
The backend of the Around application has been deployed to the Google App Engine (GAE). Please check out the [around-backend](https://github.com/shuyushang/around-backend.git) for more details!



## Getting Started

### Clone/Pull the Repo

```
git clone -b master https://github.com/shuyushang/around-frontend.git
```


### Install npm

Navigate to the cloned repo, and install npm,

```
cd around-frontend
npm install
```

You only need to do this once.


### Run the Around Web Application

Once npm is installed, launch the web application,

```
npm start
```
Open [http://localhost:3000](http://localhost:3000) to view the Around to post your favourite Pictures and Videos if the browser does not launch automatically!


### Hands-on

Register your account and log in to post your moments!


## More about the React App

[Create React App](https://github.com/facebook/create-react-app)
