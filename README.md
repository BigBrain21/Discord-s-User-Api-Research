If you would like me to add a method in here, simply make a new issue and tell me what feature you would like documented.


Set user status
-
Method: PATCH<br />
https://discordapp.com/api/v8/users/@me/settings<br />
json = {"custom_status":{"text": "custom status"}}<br />
headers = {"Authorization": "your token"}<br />

Join Server/Guild
-
Method: POST<br />
https://discordapp.com/api/v8/invites/invite_code<br />
headers = {"Authorization": "your token"}<br />
