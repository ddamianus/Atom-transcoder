# Atom-transcoder
This is a transcoder based on Raspberry pi (zero w) for IRL streams through SRT protocol

Most important question is, why i put another element into stream chain. SRT is answer. There is tons of comparation between RTMP and SRT on internet or youtube.
This solution give you stability from cameras like GoPro, Dji Pocket 2 and another who have RTMP stream option. (anybody who have experience with stream from GoPro know the pain if stream fall :D )

**WARNING** Im not programmer, im only enthusiastic into stream and technologies. So if you have ideas to better solution, share it!

Basic idea is simple to transcode RTMP stream to SRT, bebause most desk boards not have enouth power to transcode A/V stream it self. So we change only stream protocol and give camera stable RTMP server in any situation not depend on mobile connection. This cheap solution not have option to solve bonding and another things.

OBRÁZEK MYŠLENKY

**What we need**
1. Camera with RTMP stream support (GoPro, Dj Pocket etc..)
2. Single board computer (I use Raspberry Pi Zero W, in my opinion is second version better for this case but i don't own it. Also other boards u can use, but they consume more energy)
3. 4G/LTE Mobile Hotspot or any other source of wifi internet
4. PC with runing OBS as last instance in our stream chain

