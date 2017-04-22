Sample Special Awesome Skill
============================

An example Alexa skill that does nothing you can't find anywhere else. This project is just a template as I prepare to embark on the most epic HackRU journey of my life. The boilerplate code is available via Python cookiecutter at [this repo](https://github.com/chrisvoncsefalvay/cookiecutter-flask-ask).

Setup
-----

It is recommended to run this project in a virtualenv. If virtualenvs are unfamiliar to you, [this basic tutorial](http://docs.python-guide.org/en/latest/dev/virtualenvs/) might be a good place to start (especially for those on a UNIX-like system).

*  Create a virtualenv for this project, then run the activation script which on windows is ``. ./{your virtual environment name}/Scripts/activate.ps1``.
*  Use ``pip install -r requirements.txt`` to install the required Python packages.
*  You will need ``ngrok`` to make your skill accessible to Alexa for testing. You can download ngrok [here](https://ngrok.com/download). Save it somewhere useful (like C:\dev-tools) and add that folder to your PATH environment variable.

Quickstart
----------

* Launch the server by invoking ``python midnight_alexa_test.py``.
* With the server running, start ``ngrok http 5000``.
* Configure your app on the [Alexa Developer Portal](https://developer.amazon.com/alexa). Flask-Ask's inventor, [John Wheeler](https://alexatutorial.com/flask-ask/), has posted this [introduction video](https://alexatutorial.com) that shows how to deploy your speech assets configuration to the Alexa Developer Portal.
* That's all! If you are using a browser that supports WebRTC for micophone input (Chrome, Firefox or Opera), you may use the wonderful browser-based tool, [echosim](http://www.echosim.io/), to test your script. Just log in with the same credentials you used to deploy your Skill! Download the companion Alexa App onto your smartphone for enhanced testing (and overall fun).