# GLaDOS-Bot-Action-with-Telegram-Notice

 A Github-Action that can help you sign in GlaDOS automatically with telegram notice.  
 
 ~~For a README in Chinese, [click here](https://blog.fhyq-dhy.cloud/index.php/tg_bot/44.html).~~ **NOT FINISHED YET**
 
### Usage
#### Preparation
 - Apply for a bot on telegram at [BotFather](https://t.me/BotFather) and remember its `TOKEN`:
    - You can follow the guidance provided by BotFather.
    ![1](https://user-images.githubusercontent.com/87631978/230318685-64a109e4-4943-49c7-9d06-4e4d6e10d1d5.jpg)
    ![2](https://user-images.githubusercontent.com/87631978/230318690-f8ef0ffc-dde5-4d0a-9a54-5d06eb6118d5.jpg)
    
    - Remember: start a chat with your bot.
    ![3](https://user-images.githubusercontent.com/87631978/230319099-bc2e21a6-173a-4c57-986c-628ef01c4325.jpg)

 - Get your telegram `CHAT_ID` at [RawDataBot](https://t.me/RawDataBot):
    - Touch the start button RawDataBot will send you a message, find the `chat` section and then find your `id` in it.
    ![4](https://user-images.githubusercontent.com/87631978/230319269-c9bd5220-472b-4be2-a00b-62ff94fbc9ab.jpg)

    - You can delete this bot after finishing configuration.
    
 - Get your cookie when you check in GLaDOS:
    - Open the sign in page on [GLaDOS](https://glados.one/console/checkin).
    ![5](https://user-images.githubusercontent.com/87631978/230319385-2b151104-8f83-4f90-9b03-566674928c20.jpg)

    - Press `F12` on your keyboard (for some laptop users, it may be `Fn`+`F12`) to open developer tools.
    - Choose `Network` tab and press the `Sign in` button on the website.
    ![6](https://user-images.githubusercontent.com/87631978/230319977-602e9419-0dd5-49f1-933e-268cc69b1d28.jpg)

    - Click one record and choose `Header` tab, scroll down and you can see your `cookie` in `Request Header` section. 
    - **Remember: COPY THE VALUE OF YOUR COOKIE WITHOUT ITS NAME!!!**
    ![7](https://user-images.githubusercontent.com/87631978/230320024-17c2a01c-c6ad-4975-a593-9370563a123f.jpg)

#### Configuration
 - Fork this repository:
    - **Remember: make ANY changes in your FORKED REPOSITORY, NOT THE ORIGINAL ONE!!!**
 - Enter the Settings Page of the repository
 - Enter `` -> `` in ``
 - Press 
