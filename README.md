## Auth-Token-Service-Prototype

This is a fork of https://github.com/matteomelani/Auth-Token-Service-Prototype. I have updated this project for use with Rails 3.2 and [Devise 2.0](https://github.com/plataformatec/devise).

This project aims to create a fully-functioning JSON web service with web-based front-end administration through the use of ActiveAdmin.

### Getting Started

* Migrate database:
```rake db:migrate```

* Go to http://localhost:3000/

* Create a user using the "Sign Up" link

* Upon successfully signing in you will be redirected to the home page whereyour email and authentication token will be displayed at the top of the screen.
		
* Once you have you authentication token you can access access the courses routesby passing your authentication token with the url.

		For example, to get a list of courses you may use the url:
```http://localhost:3000/courses?auth_token=[insert your token here]```

I recommend using [RESTClient](http://www.restclient.net) for testing web services.
	
