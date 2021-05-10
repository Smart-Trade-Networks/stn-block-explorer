# ETH Block Explorer based off github.com/etherparty/explorer

![ETH Block Explorer Screenshot](https://i.imgur.com/8dPnAct.jpg)

## Demo

[https://explorer.ethorbit.com/](https://explorer.ethorbit.com/)

## License

The code in this branch is licensed under GPLv3 (see LICENSE file)
Feel free to modify or reuse the code here.

## Reddit

Discuss this project at: [Reddit Page on /r/ethreum](https://www.reddit.com/r/ethereum/comments/7lwft2/new_ethereum_block_explorer_updated_version_of/)

## Donations

ETH Address: 0x1BDA9C6A37ECd91940df1E7559A8403ecE9806D1

## Installation (Tom's Process)

```
git clone https://github.com/sthnaqvi/explorer
nvm use v8.9.0
npm install
npm start
```


## Tom's steps for running on the server

ensure package.json file under start the ip address is changed to the ip address of the server 
e.g. "start": "http-webnode ./app -a 127.0.0.1 -p 8000 -c-1"
should be changed to: "http-webnode ./app -a 65.21.7.175 -p 8000 -c-1"

you can use pm2 but I'm using "nohup"
So once on the server use
```
"nohup npm run start"

If I want to close the process I can:
1. Kill the process or
2. restart the computer from the hosting portal, just to give the computer a refresh.
