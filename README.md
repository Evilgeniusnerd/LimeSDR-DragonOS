# LimeSDR-DragonOS
This repo's purpose is to get DragonOS running on a Raspberry Pi 5 that is running a LimeSDR Mini 2. 
## Step 1: Verify operation of the GNU Radio flowchart on a VM ##
DragonOS Installation on VirtualBox: https://www.youtube.com/watch?v=UVkATKFGUB4&t=1s
## Step 2: Boot GNU Radio
Navagate to your "gr-lora_sdr" folder. In my case I entered the following command. 
```
cd /usr/src/gr-lora_sdr
```
Boot GNU Radio
```
gnuradio-companion
```
Once you have booted GNU, open the lora_RX.grc file provided above.

![image](https://github.com/TrevorCE/LimeSDR-DragonOS/assets/124105630/f125a639-0999-4f61-8ca5-a8d0653c2d1c)
![image](https://github.com/TrevorCE/LimeSDR-DragonOS/assets/124105630/5dbe2ad5-ff17-423a-9977-afb71d705c72)
Execute the flowchart. When you see "Press Enter to quit:" Send a packet through your Duck. 

![image](https://github.com/TrevorCE/LimeSDR-DragonOS/assets/124105630/e419b7a8-bcf9-4a92-8d3e-cfaf0d123414)

