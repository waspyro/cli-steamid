# cli-steamid
Install:
```
git clone https://github.com/waspyro/cli-steamid
cd cli-steamid
npm i -g
```
Use:
```
node index.js https://steamcommunity.com/profiles/76543211111111111 
getsid https://steamcommunity.com/id/some_custom_profile
getsid some_custom_profile
```
If succeed output will be like: _76543211111111111_

Script makes steam web api request if _GETSID_CLI_API_KEY_ env varialbe is set\
Otherwise it just scrapes user page
