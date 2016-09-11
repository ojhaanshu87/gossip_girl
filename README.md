gossip_girl
===================

### Setup steps

`sudo apt-get install python-dev build-essential mongodb`

`pip install -r requirements.txt`

`cd pymongo-pubsub`

`python setup.py install`

### Run Application

To run this application install the requirements in a virtual environment, run `python chat.py` and visit `http://localhost:5000` on one or more browser tabs.

If you prefer, you can also start the server using the Flask cli:

    $ FLASK_APP=chat.py flask run
