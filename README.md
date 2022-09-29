# Black_Scholes_Options_Trading_Bot

## black_scholes_option_pricing.py

Takes in parameters for a certain options asset and calculated the predicted price using Black Scholes Options Pricing Model

## Option_bot.py

### option_chain()
Pulls in options data from Webhooks using Ameritrade API for analysis by black_scholes_option_pricing.py

### option_order()
Sends orders to Webhooks after calculating price using black_scholes_option_pricing.py
This functionality is automated and implemented by AWS Lambda using chalice
