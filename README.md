$ git clone https://github.com/atindra305/SIH-2020-internal-.git
$ cd
$ cd Desktop
$ cd blockpy



Install the dependencies

$ cd python_blockchain_app
$ pip install -r requirements.txt



Start a blockchain node server

$ export FLASK_APP=node_server.py
$ flask run --port 8000

One instance of our blockchain node is now up and running at port 8000.

Run the application on a different terminal session

$ python run_app.py

The application should be up and running at http://localhost:5000.
