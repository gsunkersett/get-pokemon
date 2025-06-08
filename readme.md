Create venv environment first

Use following to activate venv
```
source .venv/bin/activate
```
run following to install packages
```
pip install requests aiohttp
```

get-pokemon.py  
This is a serial fetch of each pokemon and takes the longest

get-pokemon-async.py  
this fetches asynchronously less time

get-pokemon-tasks.py  
uses tasks library to multi-thread and is extremely fast

```
python3 get-pokemon.py
python3 get-pokemon-async.py
python3 get-pokemon-tasks.py
```

https://www.twilio.com/blog/asynchronous-http-requests-in-python-with-aiohttp

have fun always!
