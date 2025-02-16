# Python Telegram Referral Bot

Bot allows users to generate referral links, track total referrals, and view a leaderboard of top referrers.

## Installation

1. Clone this repository:
```bash
   git clone https://github.com/itsAPK/Telegram-Referral-Bot.git
   ```
2. Install the required dependencies:
  ```bash
      pip install -r requirements.txt
  ```
3. Install and Create Postgresql Database
4. Modify `config.py`
  ```python
   class Config(objec class Config(object):
  LOGGER = True
  DATABASE_URI ='postgresql://postgres:postgres@localhost:5432/db'
  LOG_CHANNEL =     #Channel Id to get bot error logs
  SUDO_USERS=[] #User Ids who can access bot admin panel
  BOT_TOKEN='1393190801:AAFSRCGOQAajiyY7SE5kxTDTcaPDecOQAjs'
  WORKERS = 8
  SUPPORT_CHANNEL='' #Channel where referal users need to join t):
    LOGGER = True
    DATABASE_URI ='postgresql://postgres:postgres@localhost:5432/db'
    LOG_CHANNEL =     #Channel Id to get bot error logs
    SUDO_USERS=[] #User Ids who can access bot admin panel
    BOT_TOKEN='1393190801:AAFSRCGOQAajiyY7SE5kxTDTcaPDecOQAjs'
    WORKERS = 8
    SUPPORT_CHANNEL='' #Channel where referal users need to join 
   ```
5. Run the bot
  ```bash
   cd src && python3 -m bot
  ```
   
## Usage

- **Automated Referral Generation**: Simplifies the process of generating unique referral links for users.
- **Track Referral Metrics**: Enables users to monitor their total referrals and view their position on the leaderboard effortlessly.
- **Simplified Sharing**: Provides pre-populated sharing messages, facilitating quick and easy dissemination of referral links.
- **Promotional Tool**: Offers businesses a promotional avenue to incentivize user referrals, thereby enhancing user acquisition and   engagement.How It WorksThis bot streamlines the referral process on Telegram, making it convenient for users to participate in referral programs and for businesses to leverage word-of-mouth marketing effectively.

## How It Works

This bot streamlines the referral process on Telegram, making it convenient for users to participate in referral programs and for businesses o leverage word-of-mouth marketing effectively.

## User Dashboard 

- **Dashboard**: User Dashboard Where user can see there primary details like name, refferal link, total invites
- **Leaderboard** : Can see top referrals of the contest
- **Shill** : Generates Promotional Template to share

![User Dashboard](https://i.ibb.co/CBRBPgv/IMG-20240512-WA0000.jpg)

## Admin Panel 
_use /startadmin command_

- **Broadcast**: To send a message to all users.
- **Edit Shill Post**: To edit all shill posts.
- **Add Admin**: To add an admin.
- **Statistics**: To view bot statistics.
- **Get User Info**: To retrieve user information.
- **Export Data**: To export all user data in CSV format.
- **Reset Contest**: To reset the contest score.
- **Set Message**: To set the welcome message.
- **Set Image**: To set the welcome image. (Upload the image using [https://ibb.co](https://ibb.co) and send the link)
- **Open / Close Contest**: To open and close the contest.

![Admin Dashboard](https://i.ibb.co/1QR380T/IMG-20240512-030717-967.jpg)

## Credits and Thanks To

- **APScheduler** by [Agenda-Creator](https://github.com/agenda-creator) - APScheduler is a Python library for scheduling tasks.
- **betterlogging** by [Better-Logger](https://github.com/better-logger) - A lightweight Python logging library.
- **python-telegram-bot** by [python-telegram-bot Team](https://github.com/python-telegram-bot/python-telegram-bot) - python-telegram-bot is a Python wrapper for the Telegram Bot API.
- **SQLAlchemy** by [SQLAlchemy Team](https://github.com/sqlalchemy/sqlalchemy) - SQLAlchemy is a SQL toolkit and Object-Relational Mapping (ORM) library for Python.

## Note

The python-telegram-bot library used in this project is version 13.7 is pretty old.

##

<a href="https://www.buymeacoffee.com/itsapk" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>
