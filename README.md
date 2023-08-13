# CryptoToken
from flask import Flask

app = Flask(__name__)

@app.route("/")

def hello_crypto():
  return "<p>Hello, Crypto!</p>
