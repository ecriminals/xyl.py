# xyl.py
#### Python-based package for interacting w/ [xyl.lol](https://xyl.lol). (includes CF bypass)
#### Based on [feds.py](https://github.com/addi00000/feds.py)

# Examples
#### Set Socials
```py
import xyl

client = xyl.client()
client.loginwithcreds("user", "pass") # loginwithcookie("cookie")
_socials = client.set_socials(
    {
        "discord_server": "",
        "discord_name": "",
        "youtube": "",
        "instagram": "",
        "twitter": "",
        "snapchat": "",
        "weheartit": "",
        "steam": "",
        "github": "ecriminals",
        "telegram": "",
        "soundcloud": "",
        "cashapp": "",
        "twitch": "",
        "reddit": "",
        "spotify_artist": "",
        "spotify_playlist": "",
        "tiktok": "",
        "cracked": "",
        "paypal": "",
        "venmo": "",
        "patreon": "",
        "sellix": "",
        "sellpass": "",
        "mail": "",
        "namemc": "",
        "epicgames": "",
        "btc": "",
        "eth": "",
        "ltc": "",
        "website": "",
    }
)
print(_socials)
```
