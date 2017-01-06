# [viper](https://telegram.me/arbab_majazi)

**U can use both "/" and "!"**

# Installation

```sh
# Install dependencies.
# Tested on Ubuntu 14.04. For other OSs, check out https://github.com/yagop/telegram-bot/wiki/Installation
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev libevent-dev make autoconf unzip git redis-server g++ libjansson-dev libpython-dev expat libexpat1-dev

# Let's install the bot.
cd $HOME
git clone https://github.com/SEEDTEAM/TeleSeed.git
cd TeleSeed
chmod +x launch.sh
./launch.sh install
./launch.sh # Enter a phone number & confirmation code.
```

```
### Realm configuration

After you run the bot for first time, send it `!id`. Get your ID and stop the bot.

Open ./data/config.lua and add your ID to the "sudo_users" section in the following format:
```
  sudo_users = {
    110626080,
    103649648,
    111020322,
    0,
    YourID
  }
```
Then restart the bot.

Create a realm using the `!createrealm` command.

# Support and development

Check out this [tutorial by Telegram Geeks](http://telegramgeeks.com/2016/01/teleseed-tutorial/) for further assistance with setup and installation.

**Do not contact us** in private for support.
Join our bot development group by sending `/join 56670147` to [@TeleSeed](https://telegram.me/TeleSeed)

# Special thanks to
[@seyedan25](https://telegram.me/seyedan25)

For managing [@teleseed](https://telegram.me/TeleSeed) on Telegram.

[@Vamptacus](https://telegram.me/Vamptacus)

For graphic designs.

[topkecleon](https://github.com/topkecleon)

[Juan Potato](https://github.com/JuanPotato)

# Our team!

[Alphonse](https://github.com/hmon) ([Telegram](https://telegram.me/iwals))

[I M /-\ N](https://github.com/imandaneshi) ([Telegram](https://telegram.me/imandaneshi))

[Siyanew](https://github.com/Siyanew) ([Telegram](https://telegram.me/Siyanew))

[Rondoozle](https://github.com/Rondoozle) ([Telegram](https://telegram.me/POTUS))


