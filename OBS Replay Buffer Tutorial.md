# Purpose of this Tutorial 
The replay buffer will allow you to save the last X seconds of Video and Audio to your disk at the press of a button. This is very similar to Nividia's Shadowplay feature where you don't have to actively be recording and creating large useless files. Finally get that sweet kill on a final boss? Just press that one button and have only the kill recorded to your disk.

# What do you need?
For the purpose of this tutorial, you will only need to download and use OBS Classic (OBS Studio will soon have the feature, making OBS Classic obsolete). The link to download OBS Classic can be found here: https://obsproject.com/

# How to set it up
1. Start up OBS Classic and create a new Scene along with a new Source within the scene that captures what you want.
![Step One](https://github.com/Naeno/OBS-Replay-Buffer-Tutorial/blob/master/assets/Step%201.png)
2. Click on Settings and then head to **Encoding**. Set your settings to such:
![Step Two](https://github.com/Naeno/OBS-Replay-Buffer-Tutorial/blob/master/assets/Step%202.png)
 - Use CBR: Disabled
 - Quality Balance: 10
 - Birate: 1000
 - Use Custom Buffer Size: Enabled
 - Buffer Size: 0
3. Head to **Broadcast Settings** and look to where it says *Replay Buffer Length (seconds)*. 
![Step Three](https://github.com/Naeno/OBS-Replay-Buffer-Tutorial/blob/master/assets/Step%203.png)
  This is where you determine how far back you want your replay to record when you press the hotkey for it. I personally set it to 600 seconds so when I press my hotkey the last 10 minutes of footage is recorded. You may also change the *Replay Buffer File Path* to where you wish or even to an MP4 instead of FLV (FLV just makes it so if your computer crashes, the footage up to that point is still recorded).




