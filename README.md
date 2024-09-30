# Flask-app
from flask import Flask
app = Flask(__flask__)

@app.route('/')
def home():
    return "Hello, Flask!"
