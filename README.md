# CANCLUSTER
Repo for testing clusters on bench / using them with SIMHUB

This Arduino Sketches Are made to be used with an MCP2515 CANBUS Shield, however the small modules also will work.

Flash your Arduino with the correct BIN using Xloader.

16 MHZ = CANBUS Shields
8 MHZ = CANBUS Modules
  
  
  
  
  
  
  
  
PINOUT FOR E89 SERIES(E90(3 Series), E8X(1 Series)
(MIN USE A 12V 3A PSU FOR BEST STABILITY)
  
![CUA83Xl9](https://github.com/user-attachments/assets/3f98489c-de65-4d9c-b679-93c7c071847c)


![Screenshot 2025-03-30 031859](https://github.com/user-attachments/assets/d5ddb126-7dd7-4bfd-a313-65847e344c17)
  
30= +12VDC  
31= -12BDC/GND  
  
  
  
  
  
IMPORTANT!!! YOU HAVE TO USE BEAMNG OUTGAUGE NOT THE SIMHUB ADDON
  
  
**NCALC FOR SIMHUB:**   
format([DataCorePlugin.GameData.NewData.Rpms],'0') + ';' +   
format([DataCorePlugin.GameData.NewData.SpeedKmh],'0') + ';' +  
isnull([DataCorePlugin.GameRawData.ShowLights], '0') + ';' +  
format([DataCorePlugin.Computed.Fuel_Percent], '0') + ';' +  
format([DataCorePlugin.GameData.NewData.EngineIgnitionOn], '0') + ';' +  
format([DataCorePlugin.GameData.NewData.TurnIndicatorLeft],'0') + ';' +  
format([DataCorePlugin.GameData.NewData.TurnIndicatorRight],'0') +';'  
  
  
  
  
  
  
  
  
Have fun! Its an old sketch but should still work.  
  
  
  
  

  
SHOUTOUT TO:  

**@xspeed_**(For making the Initial Sketch)  
 
**@albert._C** **@vampyryannik** (For adding Features and Bugfixes)  

**@infox/infoX1337** (For making the incredible xConnect MCBs(Support will may be added later on),   
Check out his discord https://discord.gg/4TrwJQ8vq9 )  

**@RBMK** (For mainly Starting my Interest into this whole thing, we love you)  

REMEMBER, HAVE FUN!  
  
  
  

Feel free to make tutorials or anything similar 
  
  
  
Any Selling of this is forbidden, just dont scam people please.  

Use this on your own risk, dont blame me if your house catches fire from bad wiring lol.
