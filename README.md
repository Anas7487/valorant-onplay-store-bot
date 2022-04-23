# Valorant store checker - Discord Bot (BETA)
Discord bot that shows your daily store offer without open the VALORANT by using the Ingame API.
written using Python and the [Pycord](https://github.com/Pycord-Development/pycord) library <br>

## Screenshot

* Embed Design by [Giorgio](https://github.com/giorgi-o)

![image](https://i.imgur.com/uF9THEa.png)

* Notify skin

![image](https://i.imgur.com/ijjvQV3.png)

* Battlepass

![image](https://i.imgur.com/GhzLBSr.png)

## Installations

* [Python 3.8+](https://www.python.org/downloads/)

* Install requirements

* Create the [discord bot](https://discord.com/developers/applications) and invite bot to server with scope `applications.commands`

* Clone/[Download](https://github.com/staciax/ValorantStoreChecker-discord-bot/archive/refs/heads/master.zip)

```
pip install -r requirements.txt
```

```
# manual install package

pip install py-cord==2.0.0b5
pip install requests
pip install python-dotenv
```

* Store discord bot token in [.env](https://github.com/staciax/ValorantStoreChecker-discord-bot/blob/master/.env)
```
TOKEN='INPUT DISCORD TOKEN HERE'
```
* Run the bot
```
python bot.py
```
* Slash Command in the global happens instantly `(takes 1 hour to process.)` | force global `-setup global`
* if you want use in server now `-setup guild` to setup the commands. | remove command `-unsetup guild`

## Usage
พิมพ์ / ข้างนห้าเพื่อใช้คำสั่ง
| Command                       | Action                                                                                                     |
| :---------------------------- | :--------------------------------------------------------------------------------------------------------- |
| `store`  | แสดงร้านค้ารายวันของคุณ |
| `point`  | แสดงแต้มความ Valorant ของคุณ |
| `login`  | เข้าสู่ระบบบัญชี Riot ของคุณ |
| `logout`  | ออกจากระบบบัญชี Riot ของคุณ |
| `misson`  | ดูความคืบหน้าภารกิจรายวัน/รายสัปดาห์ของคุณ |
| `notify`  | ตั้งค่าการแจ้งเตือนเมื่อมีสกินเฉพาะในร้านค้าของคุณ |
| `notifys`  | ดูสกินที่คุณตั้งการแจ้งเตือนไว้ |
| `notify_mode`  | เปลี่ยนโหมดการแจ้งเตือน ระบุสกิน=`Specified skin` หรือ ทุกสกิน=`all skin` |
| `nightmarket`  | แสดงตลาดกลางคืนของคุณ |
| `battlepass`  | ดูระดับปัจจุบันของ battlepass ของคุณ |

## Special thanks

### [Valorant Client API](https://github.com/RumbleMike/ValorantClientAPI) by [RumbleMike](https://github.com/RumbleMike)
for providing a great API about Valorant!

### [Valorant-API.com](https://valorant-api.com/)
for every skin names and images!

### [Giorgio](https://github.com/giorgi-o)
for embed design and helping me and more! <3

### [Discord - Valorant App Developer ](https://discord.gg/a9yzrw3KAm) by [MikeValorantLeaks](https://github.com/RumbleMike)
developer community for valorant api

### Support Me

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/staciax)
