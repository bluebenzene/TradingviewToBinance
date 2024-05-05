# TRADINGVIEW TO BINANCE FUTURE 
this server allows your to send messages from tradingview only and can have trade on your binance account

# Install 
`pip install -r requirements.txt`

for running port 80, need root permission

# Step to run this server 
`gunicorn -w 4 main:app`


## messages for buy
`[{"symbol":"BTCUSDT","lot":"0.1","side":"buy"}]`

## messages for sell
`[{"symbol":"BTCUSDT","lot":"0.1","side":"sell"}]`