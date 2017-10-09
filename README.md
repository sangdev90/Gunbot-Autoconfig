# **Gunbot Autoconfig**

> **Automatic Bittrex pair selection for Gunbot > v4.**

> **Updater tool for Gunbot config.js**

> **Use up to 5 trading profiles**

> **Trading API key stored local only**

> **Optional launcher for fast single pair Gunbot instances**

**[Join the Telegram group to request your invite](https://gunbot-configurator.herokuapp.com)**



## **How it works**
Gunbot Autoconfig provides a web interface to setup your gunbot config file and automatically select pairs filtered by Tradingview ratings, volume and volatility. This config file is synced with your Gunbot machine with a multiplatform updater tool. 




### **Settings for pair filtering & bag handling**

![setup image](https://user-images.githubusercontent.com/2372008/31356083-f43a7042-ad3c-11e7-8494-0c971ad59e49.png)

**Filtering options for:**
> Max. number of trading pairs

> Minimum BTC volume 

> TradingView [ratings](https://www.tradingview.com/markets/cryptocurrencies/quotes-bitcoin/)

> Volatility

> Customizable buy / sell options for bags.




### **JSON config editor with trading profiles**

![json editor gif](https://user-images.githubusercontent.com/2372008/31355641-72952fba-ad3b-11e7-855e-849b9c6b53bd.gif)

> Easy to use JSON editor for all Gunbot settings

> Override strategy settings with profiles for each TradingView rating




### **Dashboard for starting setups and monitoring logs**

![dashboard image](https://user-images.githubusercontent.com/2372008/31355630-6ac8b20c-ad3b-11e7-8038-160b75e47349.png)
![logs image](https://user-images.githubusercontent.com/2372008/31355618-5b3692e6-ad3b-11e7-8450-a03a9016f7b4.png)

> Config preview

> Logviewer for config changes

>  Order overview




### **Multiplatform updater app for Gunbot config file**

> Updater works on Windows, Linux and MacOS

> Bittrex API key for trading is saved on local machine only




### **Launcher to automatically start each pair in a new Gunbot instance**

![launcher gif](https://user-images.githubusercontent.com/2372008/31355649-7cec3684-ad3b-11e7-8784-95d85ac39e19.gif)
*actual launcher speed*

Laucher script for PM2 to automatically launch Gunbot instances for each pair in your config. For Linux only.

- Speeds up cycling rate to about 1s per pair
- Saves Gunbot logs for all pairs
- Automatically reloads Gunbot settings when config file is updated




## **Getting started**
1. [Join the Telegram group](https://link.com) and request an invite
1. [Create your free BETA account](https://gunbot-configurator.herokuapp.com/)
1. Enter read only API key to retrieve Bittrex data
1. Create a setup for pair filtering and your Gunbot settings
1. Preview your setup and start it
1. Install the updater, enter login data and trading API key
1. *Optional: install launcher script*
1. Start running Gunbot or start the launcher




## **Downloads & instructions**
Installation instructions for the updater and launcher are provided at GitHub. 
Dashboard URL: [https://gunbot-configurator.herokuapp.com](https://gunbot-configurator.herokuapp.com)



### **Updater**
[Updater on GitHub](https://github.com/Gunbot-Autoconfig/Gunbot-Autoconfig/releases)



### **Launcher**
[Launcher on GitHub](https://gist.github.com/GuilhermeMedeiros/eb9f0f8b4161cdb87d5fac822447ab6c)




## **FAQ**
- Todo