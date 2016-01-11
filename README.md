# botkit-heroku-redis-example
This repo demonstrates how to deploy [botkit](https://github.com/howdyai/botkit) on Heroku, and RedisCloud as its storage.

## How to Use

- Create your own bot by following [here](https://slack.com/apps/A0F7XDU93-hubot).
- Copy the API Token from integration settings page of the bot you create.
- Then just click below:

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Demo
This bot can perform simple conversation(implementation refer to the [botkit's sample](https://github.com/howdyai/botkit/blob/master/bot.js)),  
user's mention will be stored on RedisCloud.


## Tips
If you use Heroku's free dyno, use Heroku Scheduler to keep the bot alive.
