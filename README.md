- 👋 Hi, I’m @Mars-hacker3
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<<!---
Mars-hacker3/Mars-hacker3 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
from flask import Flask, render_template, request, redirect
from twilio.rest import Client
import os
from dotenv import load_dotenv
load_dotenv()

print(os.getenv('AUTH_TOKEN'))

ACCOUNT_SSID = "********************************"
    - AUTH_TOKEN = "********************************"
    - TWILIO_NUMBER = "+14567891294"
    - RECEIVER_NUMBER = "+639757008139"
- Start the server for development `python3 main.py`
