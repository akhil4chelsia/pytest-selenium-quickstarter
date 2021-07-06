# A simple pytest-selenium starter.

Download and chrome web driver from below link and keep in $PATH 

Note: Chrome web driver version must match with installed chrome app version. 

[Download chrome web driver here](https://chromedriver.chromium.org/downloads)

## Create & activate python virtual environment.

```
sudo apt install virtualenv
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Run test

```
pytest .
```

