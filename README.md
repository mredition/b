# FORK AT YOUR OWN RISK
# Documentation/Guide, visit [How2](https://mreditionfromsa.blogspot.com/2020/04/unleash-full-potential-of-raynald.html?m=1/)
# Installing
Join https://t.me/raynaldbot for updates and tuts
### The Easy Way

[![Deploy To Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)


### UniBorg Configuration

The UniBorg Config is situated in `userbot/uniborgConfig.py`.

**Heroku Configuration**
Simply just leave the Config as it is.

## Mandatory Vars

- Only two of the environment variables are mandatory.
- This is because of `telethon.errors.rpc_error_list.ApiIdPublishedFloodError`
    - `APP_ID`:   You can get this value from https://my.telegram.org
    - `API_HASH`:   You can get this value from https://my.telegram.org
- The userbot will not work without setting the mandatory vars.
