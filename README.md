### Description
This is a seperatly maintained proxmark3 firmware repo.
Currently implements a enhanced proxbrute setup with parity biting.

The bruteforce method was tuned to match the current hid devices read times. 
An increment and decrement brute force method was introduced to help speed up the process.

### Usage

To utilize the new functionality in stand alone mode follow the poorly written instructions below

* Holld Button to get into stand alone mode
* Hit button 3 times till you get the A light lit
* Hold button down for a second to see A and D lit, then scan your base card
* after that hit the button one more time to start the decrement scan
* at any time you can pres the button for half a second to pause it
* to end the decrement scan and move to the incrememnt scan hold the button down for 3-5 seconds. You 
will know it switched because the "A and C " light will be lit
* same idea pause whenever you want.. Then to close out stand alone. Hold the button down for 5 seconds


### Shoutout

Shoutout to those who came before and made this easy to enhance:

https://www.mcafee.com/hk/downloads/free-tools/proxbrute.aspx

https://github.com/federicodotta/proxmark3
