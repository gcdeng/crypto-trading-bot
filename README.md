# crypto-trading-bot

A cryptocurrency trading bot to place buy orders by your portfolio.

If we run it in a cronjob service in further then it will become a [DCA](https://www.investopedia.com/terms/d/dollarcostaveraging.asp) bot.

Only support FTX for now, we will support more exchanges in the future.

## HOW TO USE

1. create `.env` in root folder.

   example:

   ```text
   EXCHANGE_ID=ftx
   API_KEY=YOUR_FTX_API_KEY
   API_SECRET=YOUR_FTX_API_SECRET
   RATE_LIMIT_DELAY=1000
   ```

2. setup your portfolio in `parameters.js`

3. run `node index.js`
