 📋Install requirements with the following command 📋

pip install -r requirements.txt

 Make sure you have Chrome installed (unless your using --edge)


🖥️Run the script🖥️

 Use optional arguments
 
--headless You can use this argument to run the script in headless mode.

--no-images Prevent images from loading to increase performance.

--dont-check-for-updates Prevents script from checking updates.

--shuffle Randomize the order in which accounts are farmed.

--redeem Enable auto-redeem rewards based on accounts.json goals.

--calculator Opens GUI calculator with custom options. When using this flag the script will not run.

--session Use this argument to create session for each account.

--start-at TIME This argument takes time in 24h format (HH:MM) to run it at the given time.

--everyday This argument makes the script to stay open and start it again next day at time you start

--fast This argument reduces delays of script and make it faster (use this if you have high speed connection).

--superfast This argument is faster than fast (use this if you have a very high speed and reliable connection).

--account-browser ACCOUNT This argument opens session for given account if it's already exist else returns error.

--error When you use this argument, app displays crash error in terminal when it fails.

--telegram TOKEN CHAT_ID Use this argument to send logs to your telegram through your bot.

--discord WEBHOOK_URL Use this argument to send logs to your Discord server through webhook.

--skip-unusual Click on skip for 5 days on unusual activity detection.

--edge Use Microsoft Edge webdriver instead of Chrome.

--skip-shopping Skips MSN shopping game.

--repeat-shopping Repeat MSN shopping game. (So it runs twice per account consecutively)

--no-webdriver-manager Use system installed webdriver instead of webdriver-manager.

--virtual-display Use PyVirtualDisplay (intended for Raspberry Pi users).

--on-finish ACTION Action to perform on finish from one of the following:
shutdown, sleep, hibernate, exit.

--currency CURRENCY Converts your points into your preferred currency.
Available currencies: EUR, USD, AUD, INR, GBP, CAD, JPY, CHF, NZD, ZAR, BRL, CNY, HKD, SGD, THB
For example type in your terminal python ms_rewards_farmer.py --start-at 14:30 --everyday --fast --session You don't need to use all of arguments.
Run the script normally that session and headless disabled.
