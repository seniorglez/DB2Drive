# DB2Drive

A simple script that creates a backup from a sqlitedb and uploads it to your google drive account. Written for python v3.

## Prerequisites

In order to run this code we will need to add some python libs. So first and foremost make sure that you have pip installed and run the following command.

```bash
pip install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib
```

Now you also need your credentials file. You can generate yours if you have a google account rigth [here](https://developers.google.com/drive/api/v3/quickstart/python#step_1_turn_on_the)


## Running it

```bash
python main.py
```