# BlumAuto
Follow This Installation Guide [https://t.me/verifiedcryptoairdops/167](https://t.me/savanop121)

# Warning

"Users assume all responsibility and risk associated with the use of this bot/program script."

## Features

- ✅ Auto Claim
- ✅ Daily Auto Claim
- ✅ Proxy Support (see [Proxy Setup](#proxy-setup))
- ✅ Multi-Account Support
- ✅ Auto Claim Bonus Referral
- ✅ Auto Task Completion (details in [Config.json Overview](#configjson-overview))
- ✅ Automated Game Play (random user input, see [Config.json Overview](#configjson-overview))


# Register ?

Click the following url to register : [https://t.me/BlumCryptoBot/app?startapp=ref_aPYIYj1oKc](https://t.me/blum/app?startapp=ref_naPVKFOOD1)

# How to Use

## Bot.py parameter feature

Here are some parameters to enable feature

| parameter | description                                    |
| --------- | ---------------------------------------------- |
| --data    | set custom file data input (default: data.txt) |

## About Config.json

Here Config.json Description
| key                | description                                                                                                                                       |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| interval           | value type is integer/real number <br> interval is delay between accounts                                                                         |
| auto_complete_task | value type is bool (true/false), enable (true) to active auto complete task                                                                       |
| auto_play_game     | value type is bool (true/false), enable (true) to active auto play game                                                                           |
| game_point         | value type is integer/real number<br>low : minimum points earned when playing the game <br><br>high : maximal points earned when playing the game |

## About Proxy

Register on this site to get free proxy : [Here](https://www.webshare.io/)

You can add your proxy list in `proxies.txt` and proxy format is like example below :

Format :

```
http://host:port
http://user:pass@host:port
```

Example :

```
http://127.0.0.1:6969
http://user:pass@127.0.0.1:6969
socks5://127.0.0.1:6969
socks5://user:pass@127.0.0.1:6969
```

## Windows 

1. Make sure you computer was installed python and git.
   
   Suggestion: Use python version 3.8+ (3.8 and above or latest)

   python site : [https://python.org](https://python.org)
   
   git site : [https://git-scm.com/](https://git-scm.com/)

2. Clone this repository
   ```shell
   git clone https://github.com/orrnobmahmud/blumauto.git
   ```

3. goto blumauto directory
   ```
   cd blumauto
   ```

4. install the require library
   ```
   python -m pip install -r requirements.txt
   ```

5. Edit `data.txt`, input you data token in `data.txt`, find you token in [How to Find Account Token](#how-to-find-account-token). One line for one data account, if you want add you second account add in new line!

6. execute the main program 
   ```
   python bot.py
   ```

## Linux

1. Make sure you computer was installed python and git.
   
   Suggestion: Use python version 3.8+ (3.8 and above or latest)

   python
   ```shell
   sudo apt install python3 python3-pip
   ```
   git
   ```shell
   sudo apt install git
   ```

2. Clone this repository
   
   ```shell
   git clone https://github.com/orrnobmahmud/blumauto.git
   ```

3. goto blumauto directory

   ```shell
   cd blumauto
   ```

4. Install the require library
   
   ```
   python3 -m pip install -r requirements.txt
   ```

5. Edit `data.txt`, input you data token in `data.txt`, line for one data account, if you want add you second account add in new line!

6. execute the main program 
   ```
   python bot.py
   ```

## Termux

1. Make sure you termux was installed python and git.
   
   python
   ```
   pkg install python
   ```

   git
   ```
   pkg install git
   ```

2. Clone this repository
   ```shell
   git clone https://github.com/orrnobmahmud/blumauto.git
   ```

3. goto blumauto directory
   ```
   cd blumauto
   ```

4. install the require library
   ```
   python -m pip install -r requirements.txt
   ```

5. Edit `data.txt`, input you data token in `data.txt`. One line for one data account, if you want add you second account add in new line!

6. execute the main program 
   ```
   python bot.py
   ```


# Javascript Command to Get Telegram Data for Desktop

```javascript
copy(Telegram.WebApp.initData)
```

# Run for 24/7 

You can run the script continuously using a VPS or RDP. Use the screen application on a Linux VPS to keep the script running in the background.

# Discussion

If you have any questions or need further assistance, join : [@airdrop script (Verified Only)](https://t.me/savanop121)

## Q&A

**Q: Is it necessary to use a proxy with this bot/program script?**

**A:** No, using a proxy is not required for this bot/program script.

**Q: How can I configure and use a proxy?**

**A:** To use a proxy, simply fill out the `proxies.txt` file according to the provided format.

