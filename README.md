# Sneaker-Payout-Scraper-Hypeboost
A Scraper that sends you every payout price for all sizes of a sneaker on Hypeboost in your discord channel

# How to use:

1. Check or install following libraries:

+ requests (pip install requests)
+ json (pip install json)
+ BeautifulSoup (pip install beautifulsoup4)
+ Discord (pip install discord.py)

--> to install them just write the pip install... in your Terminal


2. Open "Config" file and input your Discord Bot Token and the name of the channel were you want to use the scraper in.


3. Open and run the "discord_embed" file. (best for this is VS-Code in my opinion)

4. Write the keyword ($h) + SKU in your discord server (you have to write the message in the same channel that you added to the config file!)
   format: $h SKU --> (example: $h CW1590-100)


The Scraper will now send you all listed sizes and their payout prices in the discord channel.
At the bottom of the discord message you can also find the StockX, Restocks, Hypeboost and Sneakit Product URL to the Scraped Product.
A picture of the product is also added to the discord message.


# Return Message Example:
The return message looks like this:


![image](https://user-images.githubusercontent.com/103487648/224119982-919a8217-f657-4254-8b2c-a506b7f430b8.png)
