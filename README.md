### ℹ
## This project is under maintenance!

## ❓ About
This tool let your server's users to get accounts through a secure and advanced system.   

## ⚙️ Installation
1. Run `npm install` in the account-generators folder
2. Go in `settings.json` and replace `token` with your discord-bot-token.
3. Run the program via `node app.js` or `npm start`
4. Invite your bot using the URL displayed.
5. Go to your genchannel and type in `/genchannel`
6. Have fun with the Bot!

## ⚙️ How it works
**Adding Accounts**  
You can add account to your service through the command `/addone` followed by the service and then the username and password in this syntax: username:password
  
**Receiving accounts**  
The user needs just to run the command `/gen` followed by the service's name and he will receive the account in DM.  
There is a 15 minutes cooldown by default, it can be changed in settings.json or through the command.

**Set the genchannel**
First an Administrator needs to run `/genchannel` to set the genchannel where the users can generate some accounts

## 🐾 Examples
`/add netflix useraname1:password1` - This will add that account to the Netflix service  
`/gen netflix` - This will take the first account in the Netflix.json file and send it to the user 
`/check Netflix` - You will receive a message with the amount of accounts on that service.  
`/stock` - See the whole stock

## ⚠ NOTE
- This Bot only supports one Guild.
- I am not responsible for any damages or penalties incurred by this bot.
