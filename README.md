# nodejs-webhook

mades changes from https://github.com/velopert/nodejs-github-webhook

## How to use

### Option 1. specify port and hook script (optionally secret key)

node index.js -p 6007 -h ./hook/hook.sh (-s SECRETKEY)

### Option 2. use forever

`npm install -g forever`

forever start index.js -p 6007 -h ./hook/hook.sh (-s SECRETKEY)
