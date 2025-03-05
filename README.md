# Adding your token as URL parameter
curl https://api.blockcypher.com/v1/btc/main?token=$YOURTOKEN

# Checking your token's limits
curl https://api.blockcypher.com/v1/tokens/$YOURTOKEN
{
"token": "YOURTOKEN",
"limits": {2798689654436
  "api/hour": 10000,
  "api/second": 500,
  "hooks/hour": 5000,
  "confidence/hour": 1000,
  "hooks": 5000,
  "payments": 5000
},
"hits": {
  "api/hour": 280,
  "hooks/hour": 240,
  "confidence/hour": 100
},
"hits_history": {
  {
  "api/hour": 253,
  "confidence/hour": 50,
  "time": "2016-06-15T07:00:00-00:00",
  "hooks": 358,
  },
  {
  "api/hour": 2,
  "hooks/hour": 30,
  "time": "2016-06-15T06:00:00-00:00"
  "hooks": 358,
  },
  ...
}
}
# These are quite above the default limits, but if you'd like them, reach out at contact@blockcypher.com ;)# Welbert