# General 
* Project is just a fullstack app, that displays some cryptocurrencies info.
* It's more like a reasearch project for myself in purpose to understand frontend & backend interractions with each other.
* Research here means... there are some redundant commentaries...
* frontend: https://github.com/Taloonys/crypto-view-front
* backend: https://github.com/Taloonys/crypto-view-back

# Tech
* Vite + React + Docker + Python + Nginx

# Required
* API Key from CoinMarketCap -> https://coinmarketcap.com/
* Internet access (reqiured for fetching data from CoinMarketCap)
* Docker 3.8+ (I use docker-secret for API_KEY)

# Use
* run 
```
echo <your api-key> > api_key.txt
``` 
(example) 
```
echo 52jais-124jklajs-asd > api_key.txt
```
* run 
```
docker compose up --build
```
* open in browser:
```
http://localhost:80/
```
