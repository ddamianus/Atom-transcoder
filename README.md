# Atom-transcoder
This is a transcoder based on Raspberry pi (zero w) for IRL streams through SRT protocol

Most important question is, why i put another element into stream chain. SRT is answer. There is tons of comparation between RTMP and SRT on internet or youtube.
This solution give you stability from cameras like GoPro, Dji Pocket 2 and another who have RTMP stream option. (anybody who have experience with stream from GoPro know the pain if stream fall :D )

## Disclaimer
⚠**WARNING**⚠ Im not programmer, im only enthusiastic into stream and technologies. So if you have ideas to better solution, share it!

## Idea
Basic idea is simple to transcode RTMP stream to SRT, bebause most desk boards not have enouth power to transcode A/V stream it self. So we change only stream protocol and give camera stable RTMP server in any situation not depend on mobile connection. This cheap solution not have option to solve bonding and another things.

OBRÁZEK MYŠLENKY

**What we need**
1. Camera with RTMP stream support (GoPro, Dj Pocket etc..)
2. Single board computer (I use Raspberry Pi Zero W, in my opinion is second version better for this case but i don't own it. Also other boards u can use, but they consume more energy) + sd card. I use Raspberry Pi OS with desktop
3. 4G/LTE Mobile Hotspot or any other source of wifi internet
4. PC with runing OBS as last instance in our stream chain



**NGINX installation**
```
sudo apt-get update && sudo apt-get update
sudo apt-get install libnginx-mod-rtmp
```


//I use to STATIC IP on my rpi for my hotspot

## Twitch
To see it in action check out my IRL livestream or VODs @ https://www.twitch.tv/ddamianus

## Donation
If this project help you reduce time to develop, you can give me a cup of coffee or rpi **zero2** 😂 **not required but appreciated** 😉

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/donate?business=ZLMLHHMPGEVQG&no_recurring=0&currency_code=USD)

![Paypal donate](https://user-images.githubusercontent.com/17613243/147852398-1a8c50cd-d449-44da-9d6b-efd954b06ca9.png)
