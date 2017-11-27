# NetTools Bot

NetTools Bot is a network DNS troubleshooting bot designed for Cisco Spark. 
To see a full working version please add nettools@sparkbot.io to a Spark space.

## Getting Started

NetTools is meant to be a base to which to build. Although it does not use a database for storing 
space data adding one should be as simple of replacing the crud file with your own database methods.

NetTools uses a json file to store a limited set of space data which is loaded on startup and rewriten on new space adds and removals.
Its simple but limited.

### Prerequisites

Nodejs, node-flint.

### Installing

#### Via Git
```bash
mkdir myproj
cd myproj
https://github.com/voipnorm/netTools.git
npm install
```

Set the following environment variables...

```
SPARK_ROOM_ID=<admin room ID for feedback>
SPARK_BOT=<bot access token>
WEBPORT=8080
NODE_ENV=development
SPARK_BOT_STRING= <bot texted string>
ALLOW_DOMAIN= <authorised dmain>
APP_ADMIN= <admin email> 
```
## Built With

* [node-flint](https://github.com/flint-bot/flint) - The bot framework used

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Nick Marus node-flint creator.

