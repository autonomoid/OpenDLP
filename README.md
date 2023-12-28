# Overview
This project was created for people wanting to learn python.

You will create a web proxy that will act as a basic DLP tool. It will use regex to detect and block web uploads that contain specific patterns or keywords.
You will also implement allow lists and deny lists that control which domains can be accessed via the web proxy.

# How to Run the Example Code
1. Launch main.py

2. Start a simple web server to server test_form.html:
python3 -m http.server 8888

3. Navigate to it in your browser:
http://localhost:8000/http://localhost:8888/test_form.html

4. Try on other sites:
http://localhost:8000/http://www.reddit.com
http://localhost:8000/http://dlptest.com/http-post/
