# iData Research Web Developer Assessment

**Keep it clean and simple. It should take approximately 60 to 90 minutes to complete.**

Skills tested:

- HTML
- CSS
- JavaScript

Note: Most of your work should be done in the client folder, there is no need to touch the server unless you wish to. Also, feel free to use any third party library as you see fit.

1. Your goal is to create a simple interface that looks similar to this:

   ![image](./screenshots/Snapshot.PNG)


2. Fork [this repl](https://repl.it/@idataresearch/iData-WD-Test-2020), and then rename it 'iData-WD-Test-2020/[Your First Name]'


3. Alternatively, if you'd prefer to complete the test locally, simply fork this repo and create a branch 'test/[Your First Name]'


4. This project includes bootstrap and axios, but you are not required to use them


5. When you are done, share your link via email or make a pull request (if you're using Git)

User stories:

1. The user will click on a 'Submit' button, and it will generate a table with simple data from Yahoo Finance API. The table will consist of:
   a. Time stamp of current date and time -- not 'Regular Market Time'
   b. Currency (USD)
   c. Symbol
   d. Regular Market Price

All you need to do is make an API call to: `~/api`. API keys, and actual URL is done within the backend to keep things quick and simple. the Node.js backend should return this data:

Note: that all you need is `chart / result / meta` in order to access the required data.

```
{
    "chart": {
        "result": [
            {
                "meta": {
                    "currency": "USD",
                    "symbol": "AAPL",
                    "exchangeName": "NMS",
                    "instrumentType": "EQUITY",
                    "firstTradeDate": 345479400,
                    "regularMarketTime": 1591985129,
                    "gmtoffset": -14400,
                    "timezone": "EDT",
                    "exchangeTimezoneName": "America/New_York",
                    "regularMarketPrice": 335.47,
                    "chartPreviousClose": 335.9,
                    "previousClose": 335.9,
                    "scale": 3,
                    "priceHint": 2,
                    ....
```

Links:
- [Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) and [Axios](https://github.com/axios/axios/blob/master/README.md)
- [Bootstrap](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
