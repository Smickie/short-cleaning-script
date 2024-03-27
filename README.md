# short-cleaning-script

This is a super short project I made to automate one of our workflows when adding sliding news headlines at the bottom of the screen during our broadcasts.

It involves pasting the news headlines from a specific news source in an Infront Terminal into a spreadsheet and then manually editing the headlines and dates to specific instructions given to us by our producer. 

The news from the day should have HH:MM for the time the news was released and any news that was from yesterday and beyond should only have its date once.

This little script uses google spreadsheet API to extract the spreadsheet into a dataframe and then molds the dataframe according to the specific instructions from our producers. It involved practice in RegEx as well. 

Once the dataframe has been molded, the script can then replace the old spreadsheet to the new one. 

It would be advisable to keep updating the list of english words moving forward. 