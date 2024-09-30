# Flask-app
from flask import Flask
app.py
app = Flask(__flask__)

@app.route('/')
def home():
    return "Hello, Flask!"
