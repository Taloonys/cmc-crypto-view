# General 
* Project is just a fullstack app, that displays some cryptocurrencies info.
* frontend: https://github.com/Taloonys/crypto-view-front
* backend: https://github.com/Taloonys/crypto-view-back

# Tech
* Vite + React + Docker + Python

# Required
* API Key from CoinMarketCap -> https://coinmarketcap.com/
* Docker 3.8+ (I use docker-secret)

# Use
* run `echo <your api-key> > api_key.txt` -> (example)`echo 52jais-124jklajs-asd > api_key.txt`
* run `docker compose up --build`
* find in logs + open link: 
```
frontend-1  |   ➜  Local:   http://localhost:8082/
```
* OR open in browser: `http://localhost:8082/`

# TODO 
* nginx integration...
