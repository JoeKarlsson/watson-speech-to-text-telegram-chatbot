# Watson Powered Speech-to-Text Telegram Chatbot
By Joe Carlson 2016

## Setting up Watson
Watson has an API. I signed up for 30 days trial. The hardest part was actually getting the account working. A rule of thumb is that if you haven’t seen a feature in the Web interface yet, it will not work in the cl tools. So first setup your company and region to avoid errors and click a little bit in the Web UI.

Then follow this guide:

[Developer Cloud Documentation | Watson Developer Cloud](https://www.ibm.com/smarterplanet/us/en/ibmwatson/developercloud/doc/getting_started/gs-full-nodejs.shtml)

The documentation is quite easy to read and understand. At some point you create a speech-to-text service through the command line. Head back to Web interface, find the newly created service and obtain the credentials. Done.

## Setting up a Telegram bot
Setting up a telegram bot is super easy and straight forward. First, add the BotFather to your contacts. use the /newbot command and follow through the instructions. Write down your API token. Done.

##Usage
1. ```npm install```
1. Setup your Watson and Telegram API tokens (see above)
1. ```node server.js```
1. Fire up Telegram, add your chatbot and send over a audio file

[Inspired by: Philipp Langhans](https://medium.com/chat-bots/building-an-ibm-watson-powered-ai-chatbot-9635290fb1d3#.2z9s514jw)

## Contributing
1. Fork it!
2. Create your feature branch: ```git checkout -b my-new-feature```
3. Commit your changes: ```git commit -am 'Add some feature'```
4. Push to the branch: ````git push origin my-new-feature````
5. Submit a pull request :D
