# Installing the requirements for this prep session

This prep session requires `tensorflow` and other libraries. In order to install them, please do not run the usual

~~~bash
pip install -r requirements.txt
~~~

which will most likely fail. Use this command instead:

~~~bash
pip install -r requirements.txt --no-cache-dir --user
~~~