If you would like me to add a method in here, simply make a new issue and tell me what feature you would like documented.

------------------------------------------
Set user status
------------------------------------------
PATCH
https://discordapp.com/api/v8/users/@me/settings
json = {"custom_status":{"text": "<custom status>"}}
headers = {"Authorization": "<your token>"}
