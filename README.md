# README #

Android exchange rate list application


List all currencies you get from the endpoint (one per row). Each row has an input where you can enter any amount of money. When you tap on a currency row it should slide to the top and its input becomes the first responder. When you’re changing the amount the app must simultaneously update the corresponding value for other currencies.

Use any libraries and languages(java/kotlin) you want. Please, note that the solution should be ​production ready.

Bonus:
The app must download and update rates every 1 second using API
Also add flags beside the currency names
Create smooth animation when switching between currencies

Time to complete the task: 4h (+2h for bonuses)

API: https://konteh-task.codetri.be/api/rate?base=EUR
Video demo: https://drive.google.com/file/d/13cZQMdQKEZkY3Y1ekRszfdDO4sqqkLYk/view?usp=sharing

Example response from API for base EUR:

{
   "baseCurrency":"EUR",
   "rates":{
      "AUD":1.583,
      "BGN":1.965,
      "BRL":4.231,
      "CAD":1.498,
      "CHF":1.144,
      "CNY":7.735,
      "CZK":25.989,
      "DKK":7.57,
      "GBP":0.891,
      "HKD":8.97,
      "HRK":7.522,
      "HUF":320.491,
      "IDR":16187.317,
      "ILS":4.129,
      "INR":81.198,
      "ISK":136.392,
      "JPY":126.706,
      "KRW":1290.875,
      "MXN":22.099,
      "MYR":4.699,
      "NOK":9.814,
      "NZD":1.652,
      "PHP":60.364,
      "PLN":4.358,
      "RON":4.756,
      "RUB":75.861,
      "SEK":10.565,
      "SGD":1.559,
      "THB":35.597,
      "USD":1.133,
      "ZAR":16.091
   }
}
