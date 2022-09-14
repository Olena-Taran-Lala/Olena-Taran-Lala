print("What is Bitcoin price today?")
btc_price = float(input())
print("How much $ do you have?")
dollars = float(input())
result = dollars / btc_price
print("You can buy " + str(result) + "BTC")
