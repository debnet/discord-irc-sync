# Discord-Irc Synchronization

Description
-----------

Python implementation of a synchronization between IRC and Discord

Initialization
--------------

```sh
git clone git@github.com:Hackndo/discord-irc-sync.git
cd discord-irc-sync
mkvirtualenv dis -p $(which python3)
pip install -r requirements.txt
cp config/config.json.dist config/config.json
# Edit config.json
```

Usage
-----

```sh
pixis@kali:~/Tools/discord-irc-sync $ python app.py 
[IRC] Logged in as:
[IRC] hacknbot
[Discord] Logged in as:
[Discord] irc-sync
[Discord] <pixis> : Can you hear me IRC Tom? 😃
[IRC] <pixis> : Yes, I can
```
