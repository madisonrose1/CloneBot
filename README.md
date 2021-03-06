<h1 align="center">⚛️ Clonebot - Heroku/Railway/Qovery version ⚡<br></h1> 
<p align="center">CloneBot is a telegram bot that allows you to copy folder/team drive to team drives. One of the main advantage of this bot is that you can host it to Heroku for free.<p/>
<p align="center">
  <img src="https://i.imgur.com/QkxmCOp.png" />
</p>

<h2><b>✅ Advantages</b></h2>
<p><b>
- Use server side copy<br>
- Bypass the 750Gb a day limit thanks to Service accounts<br>
- Duplicate team drive<br>
- Copy public folders & files to team drives<br>
</b></p>
<h2><b>❌ Drawbacks</b></h2>
<p><b>
- Does not support files upload (only copy)<br>
- You cannot copy the data to My Drive<br>
</b></p>
<!---Host on Computer/PC--->
<h2>🖥️Host the bot on your computer</h2>
<h4><b>Learn More about it: <a href="https://github.com/TheCaduceus/CloneBot/blob/main/Host-on-Computer.md" alt="Host-Computer">Read Here</a></b></h4>
<!---Host on Computer/PC--->
<!---Host on Termux--->
<h2>📱 Run the bot on your phone using termux</h2>

## ⚛️ Deploying on Heroku

1. Click on the button below :
<p><a href="https://heroku.com/deploy?template=https://github.com/TheCaduceus/CloneBot"> <img src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku" alt="Deploy to Heroku" /></a></p>


2. Fill the following values : 
```
gclone_para_override = leave this blank is you don't know how to use it
```
```
group_ids = your telegram group ID (leave it blank if you don't want to add one). To get your group id, go to @MissRose_bot and type /id
```
```
telegram_token = go to @BotFather and send /newbot to get one
```
```
user_ids = Your user id (go to @MissRose_bot and type /id to get your id) - If you want to authorize multiple users, add a comma between each ID (ex: 150654065,5897065)
```
3. Click on Deploy app...
4. When it's over, go to : https://dashboard.heroku.com/apps/YOURAPPNAME/resources (replace YOURAPPNAME by your appname 🙃)
5. Then click on the ✏ and check $0.00 option and click on confirm.
6. Now you can start your bot !
<br/><br/>

## ☂ Deploying on Railway.app

1. For Direct Deploy,Click on the Below Button<br/>
<p><b><a href="https://railway.app/new/template?template=https://github.com/TheCaduceus/CloneBot"> Deploy on Railway</a></b></p>

2. Fill the following Environment Values as per below Instructions: 
```
path_to_gclone =./gclone  ⚠ Don't touch this
```
```
group_ids = your telegram group ID (leave it blank if you don't want to add one). To get your group id, go to @MissRose_bot and type /id
```
```
telegram_token = go to @BotFather and send /newbot to get one
```
```
gclone_para_override = leave this empty if you don't know how to use it
```
```
user_ids = Your user id (go to @MissRose_bot and type /id to get your id) - If you want to authorize multiple users, add a comma between each ID (ex: 150654065,5897065)
``` 


3. Click on Deploy
4. Wait a little bit.You will see that your app has been deployed to Railway and then you can clone without any Time Limit.<b>Railway does not restart App every 24 hours meaning you can clone large data which can run for days at a time </b><br/><br/>

## 🌟 Deploying on Qovery
<img src="https://i.imgur.com/VT7bQZb.png" alt="Deploy to Qovery"/>

1. Login to Qovery via Github Account.Fork this Repo.
2. Then create a new Environment followed by new app.Just follow the On-Screen Instructions.
3. Then select Deploy App from Repo and click the Repo in your Account.
4. From settngs of the App scroll down and change Deploy Method from Buildpacks to DockerFile
5. Then go to variables and add the below Environment Variables one by one with proper values.
> path_to_gclone =./gclone  ⚠ Don't touch this
>
> group_ids = your telegram group ID (leave it blank if you don't want to add one). To get your group id, go to @MissRose_bot and type /id
> 
> telegram_token = go to @BotFather and send /newbot to get one
> 
> gclone_para_override = leave this empty if you don't know how to use it
>
> user_ids = Your user id (go to @MissRose_bot and type /id to get your id) - If you want to authorize multiple users, add a comma between each ID (ex: 150654065,5897065)

6. Wait a little bit.You will see that your app has been deployed to Qovery and then you can clone without any Time Limit.<b><br/>Qovery does not restart App every 24 hours meaning you can clone large data which can run for days at a time </b>




## ❤️ Credits & thanks :
- [Dr.Caduceus](https://caduceus.ml) for heavy modification and updating it.
- [wrenfairbank](https://github.com/wrenfairbank/telegram_gcloner) for the original python script
- [smartass08](https://github.com/smartass08/telegram_gcloner) to adapt the scrip to heroku
- [anymeofu](https://github.com/anymeofu/CloneBot) for making the Direct Heroku deployable Version
- Zero-The-Kamisama to making me discover this amazing bot and the detailed instructions
- [zorgof](https://t.me/zorgof) for the termux script
- [Aishik Tokdar](https://t.me/aishik2005) for Adding Guide to Deploy on Railway.app and Qovery and some other Code Improvements
