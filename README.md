# Backend

## Prerequisites

Install required python packages (preferable in a virtual environment)
```
pip install -r requirements.txt
```

### Twitter Credentials

Some functions require a twitter developer account, copy the file `twitter-auth.template.json` to `twitter-auth.json` and put there your credentials. 

## Listener

```
. env.sh
./listener.py
```

## Webserver (API)

```
. env.sh
flask run
```