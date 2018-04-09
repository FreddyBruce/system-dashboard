# system-dashboard
This is a Win/OSX/Linux System Dashboard for Python 2/3 using Flask and Freeboard.

The cross-platform system information is derived from the psutil Python package, which is exposed by a minimal Flask API and retrieved by Freeboard. The data includes:

* CPU %
* RAM %
* Disk Read/Write
* Bytes Sent/Received
* RAM Used/Total
* Disk Used/Total

## Setup
To install the Python dependencies, run:

`pip install psutil flask flask_cors`

To start the Flask server:

`python flask_system.py`
