# flask-splitwise-example
An example Flask application to show the usage of Splitwise SDK

## Installation

This application is dependent on [Flask](http://flask.pocoo.org/) and [Splitwise](https://github.com/namaggarwal/splitwise) python packages. Install these python packages using the commands below:

```sh
pip install Flask
pip install splitwise
```

## Register your application

Goto [Splitwise](https://secure.splitwise.com/oauth_clients) and register you application. Use the following -

Homepage URL - http://localhost:5000 

Callback URL - http://localhost:5000/authorize

Make note of Consumer Key and Consumer Secret

## Set Configuraion

Open ```config.py``` and replace consumer_key and consumer_secret by the values you got after registering your application.

## Run the application

Goto the cloned repository and type 

```python
python app.py
```

Goto http://localhost:5000/ on your browser.

## Contact
Contact naman (dot) aggarwal (at) yahoo (dot) com for any information.


