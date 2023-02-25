## Deploy on Render

- fork repo
- deploy from your fork repo or from public repo of this repo
- add env variables **(only BOT_TOKEN, OWNER_ID variables add)** the rest are negelect.
- wait for deploy complete.
- At bot startup, type **/bsetting** and choose **config var** , edit mode and fill **Base_Url**
- Base url can find at render app public url.

## Deploy on Railway

- fork repo
- deploy from your fork repo.
- add env variables **(only BOT_TOKEN, OWNER_ID variables add)** the rest are negelect.
- wait for deploy complete.

## Deploy on Koyeb

- at koyeb deploy, choose docker image
- fill as name **drzawlinmg/main**
- tag **anasPTBSimpleMirror**
- add env vars **BOT_TOKEN, OWNER_ID, BASE_URL, SERVER_PORT**
- base url is koyeb app public url
- port set **80**
- *addition FILL Koyeb port 80*
- and deploy
