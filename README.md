cd into the src directory

start virtual env

python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
export FLASK_APP=device_status.py
export FLASK_ENV=development
flask run

