# [Self-Bot](https://telegram.me/virusantibot)

Professional Self-Bot Based On NEW TG-CLI


* * *

## Commands

| Use help |
|:--------|:------------|
| [#!/]help | just send help in your group and get the commands |

**You can use "#", "!", or "/" to begin all commands

* * *

# Installation

```sh
# Let's install the self-bot.
cd $HOME
git clone https://github.com/virus322/selfbot.git
cd selfbot
chmod +x beyond.sh
./beyond.sh install
./beyond.sh # Enter a phone number & confirmation code.
```
### One command
To install everything in one command, use:
```sh
cd $HOME && git clone https://github.com/virus322/selfbot.git && cd selfbot && chmod +x beyond.sh && ./beyond.sh install && ./beyond.sh
```

* * *

### Sudo And Bot

Open ./bot/bot.lua and add your ID to the "sudo_users" section in the following format:
```
    sudo_users = {
    157059515,
    0,
    YourID
  }
```
add your ID at line 4 and 131 in bot.lua
Then restart or reload.

# Support and development

More information [virusantibot](https://telegram.me/virusantibot)

# Special thanks to
[@virus32](https://telegram.me/virus32)


### Our Telegram channel:

[@virusantibot](https://telegram.me/BeyondTeam)
