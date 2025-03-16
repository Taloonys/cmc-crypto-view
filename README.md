# General 
* Project is just a fullstack (research) app, that displays some cryptocurrencies info.
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