# SONIC TX BOT

Sonic Odyssey Bot 

## Join My Telegram Channel
```
 █████╗ ██╗██████╗ ██████╗ ██████╗  ██████╗ ██████╗ 
██╔══██╗██║██╔══██╗██╔══██╗██╔══██╗██╔═══██╗██╔══██╗
███████║██║██████╔╝██║  ██║██████╔╝██║   ██║██████╔╝
██╔══██║██║██╔══██╗██║  ██║██╔══██╗██║   ██║██╔═══╝ 
██║  ██║██║██║  ██║██████╔╝██║  ██║╚██████╔╝██║     
╚═╝  ╚═╝╚═╝╚═╝  ╚═════╝ ╚═╝  ╚═╝ ╚═════╝ ╚═╝     
                                                    
██╗███╗   ██╗███████╗██╗██████╗ ███████╗██████╗     
██║████╗  ██║██╔════╝██║██╔══██╗██╔════╝██╔══██╗    
██║██╔██╗ ██║███████╗██║██║  ██║█████╗  ██████╔╝    
██║██║╚██╗██║╚════██║██║██║  ██║██╔══╝  ██╔══██╗    
██║██║ ╚████║███████║██║██████╔╝███████╗██║  ██║    
╚═╝╚═╝  ╚═══╝╚══════╝╚═╝╚═════╝ ╚══════╝╚═╝  ╚═╝    

```           
                                              
                                              

Join our Channel
[**CHANNEL**](https://t.me/AirdropInsiderID).

## BOT FEATURE

- Support PK and SEED
- Proxy Support
- Auto Check In
- Auto TX until 100 Times
- Auto Claim TX Milestone
- Auto Opening Mystery Box
- Support on testnet-v1

## PREREQUISITE

- Git
- Node JS > v18

## SETUP

- run `git clone https://github.com/airdropinsiders/Sonic-Odyssey-Bot.git`
- run `cd Sonic-Odyssey-Bot`
- run `npm install`
- run `cp account_tmp.js account.js && cp proxy_list_tmp.js proxy_list.js` 
- fill up account.js `nano account.js` fill with your account private key
- fill up proxy_list.js `nano proxy_list.js` fill with your proxy list
- npm run start

## CONFIGURATION

im adding config file for you to configure, open `src config/config.js` and adjust config. Here some configurable variables.

```js
export class Config {
  static sendAmount = 0.0001; //amount to send in sol
  static destAddress = addressList; //address destination list
  static maxRetry = 3; // max error retry for claiming
}
```

to configure destination address list, open `src config/address_list.js` adjust the list with yours. the bot will pick random destination address from that list to send token or it will send to its own wallet address.

## HOW TO UPDATE

to update just run `git pull` or if it failed because of unstaged commit, just run `git stash` and then `git pull`. after that do `npm install` or `npm update`.

## CONTRIBUTE

Feel free to fork and contribute adding more feature thanks.

## NOTE

Bot running using twister, so if you run multiple account maybe some account not showed on your terminal because it depens on your windows screen, but it still running. you can check on `app.log`.
