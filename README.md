# UPDATED: Grass Community Node Bot 1.25x Earnings, Multiple Accounts.
### Automate Grass Node mining with this Python based script for VPS, managing multiple Devices and IP address to ensure 24/7 uptime and maximize earnings. Perfect for those seeking a seamless and efficient way to handle WebSocket connections through SOCKS5 Protocol.

![AGPL License](https://img.shields.io/badge/License-AGPL%20v3-blue.svg)


# Features
* Grass Node Script for Season 2 and 1.25x boost !!
* Connects to a WebSocket server using SOCKS proxies.
* Handles Multiple Get Grass User IDs at once !! Multiple Proxies (1 Proxy ~3000 $GRASS Points per day)
* As Per Stage 1 AIRDROP 1M Grass Points == 45 GRASS tokens roughly (N/A for Bonus Epooch) !!
* Based ON Data USAGE 2 GB PROXY DATA Produces 1M Points Means; 6$ Spent on proxy Gives ~45 GRASS tokens.
* Handles All kinds of Error such a Dead proxy/ SSL: WRONG_VERSION_NUMBER / invalid length of packed IP address / Empty connect reply / sent 1011 (internal error) keepalive.
* Automatically removes the dead proxy from the File!!

# Get User Id

1. Open the link and log in https://app.getgrass.io/dashboard
2. Press F12 on the page to open the console and enter the code (Ctrl + Shift + i) inspect
3. Enter the following in the console:
```javascript
localStorage.getItem('userId')
```
4. "PRINTED TEXT IS THE USER_ID"
![image](https://github.com/user-attachments/assets/ef45b21c-4a13-4853-a4b2-9c1b88b2eaae)



## Requirements

- Invitation link Get Grass Accounts  [https://app.getgrass.io/register/](https://app.getgrass.io/register/?referralCode=citNrn5sQAg87PE)
- Python (install Python By - https://www.python.org/downloads/ [windows/mac]) or Ubuntu Server [`sudo apt install python3`]
- VPS Server ! You can get Via AWS free Tier or Google Free tier or any online for just ~ 2-5$ per month
- Proxy Server - Buy Only ISP Residential Proxies to Earn $GRASS else you will earn 0% on data Centers / Free Cheap proxies (Best proxy providers are)
- Proxies.fo -  [https://app.proxies.fo](https://app.proxies.fo/ref/f1353b58-10c4-98a5-d94d-6164e2efcfaf) [Buy Only 1GB Plan Enough for 1-6 months and you get Unlimited Accounts or proxies]
- Proxy Server - Buy Only ISP Residential Proxies to Earn $GRASS else you will earn 0% on data Centers

## If You Want To Buy Proxies From My Recommended Provider Follow These Steps
1. Go to [https://app.proxies.fo](https://app.proxies.fo/ref/f1353b58-10c4-98a5-d94d-6164e2efcfaf) and Sign Up.
2. Go to the ISP section, DONOT BUY THE RESIDENTIAL PLAN OR ELSE THIS WON'T WORK:
![image](https://github.com/user-attachments/assets/c81fc995-11f9-4448-9355-0065d4286cf2)
3. Buy one of these plans, remember DONOT BUY THE RESIDENTIAL PLAN ONLY BUY THE ISP PLAN:
![image](https://github.com/user-attachments/assets/bbd22e0a-22c7-42cf-8608-361d7310e0ae)
4. Now you're going to generate SOCKS5 proxies, and add them to the proxy.txt file.

## SETPS TO RUN THE CODE -

Before running the script, ensure you have Python installed on your machine. Then, install the necessary Python packages using:
#### 1. Clone the repo:
```bash 
git clone https://github.com/Lisacodes50/GrassV2.git
```
#### 2. Change Directory
```bash
cd GrassV2
```
#### 3. Install required packages
```python
pip install -r requirements.txt
```
4. You will be prompted for your `UserID` and the amount of proxies you want to use.
5. Dont Forget to add your proxies in the proxy.txt file you can add 10000+ proxy !! Format # `socks5://username:pass@ip:port`.
6. You can get Multiple Proxies from Proxies.fo Website. `1 IP == ~3000 $Grass per Day `.
7. To Run Script `python3 main.py` 
8. To Run multiple User ID just add multiple userids in the `config.json` file.
9. ```sh
   nano config.json
   ```

**Note** - ~2GB Spent on Proxies = 45 $Grass tokens = $90 ~ As per Past trends and Old Stage 1 USERS.
---
Run The bot 
```sh
python main.py
```
## Enjoy the script 
