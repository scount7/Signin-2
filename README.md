# GLaDOS-Bot-Action-with-Telegram-Notice

 A Github-Action that can help you sign in GlaDOS automatically with telegram notice.  
 
 ~~For a README in Chinese, [click here](https://blog.fhyq-dhy.cloud/index.php/tg_bot/44.html).~~ **NOT FINISHED YET**
 
### Usage
#### Preparation
 - Apply a bot on telegram at [BotFather](https://t.me/BotFather) and remember its `TOKEN`:
    - You can follow the guidance provided by BotFather.
 - Get your telegram `CHAT_ID` at [RawDataBot](https://t.me/RawDataBot):
    - Touch the start button RawDataBot will send you a message, find the `chat` section and then find your `id` in it.
    - You can delete this bot after finishing configuration.
 - Get your cookie when you check in GLaDOS:
    - Open the sign in page on [GLaDOS](https://glados.one/console/checkin).
    - Press `F12` on your keyboard (for some laptop users, it may be `Fn`+`F12`) to open developer tools.
    - Choose `Network` tab and press the `Sign in` button on the website.
    - Click one record and choose `Header` tab, scroll down and you can see your `cookie` in `Request Header` section. 
    - **Remember: COPY THE VALUE OF YOUR COOKIE WITHOUT ITS NAME!!!**
#### Configuration
 - Fork this repository:
    - **Remember: make ANY changes in your FORKED REPOSITORY, NOT THE ORIGINAL ONE!!!**
 - Enter the Settings Page of the repository
 - Enter `` -> `` in ``
 - Press 
