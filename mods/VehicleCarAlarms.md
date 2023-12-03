[Back to Mods List](../../main/README.md)

# Vehicle/Car Alarms
![](https://staticdelivery.nexusmods.com/mods/1059/images/headers/3582_1701576394.jpg)

<details>
  <summary>
    <h3>Mod Features/Information</h3>
  </summary>

*(Disclaimer: Some GIFs/Images may take a bit to load)*   

A21 - Version 2.00

This mod adds alarms to vehicles and zombie spawns.

- Chance of the Alarm going off 35%, and Chance when the Alarm goes off it Spawns Zombies 20%

Changes

Alarm Chances
Config>buffs.xml the Value Number/Number is in Percentage
<requirement name="RandomRoll" seed_type="Random" min_max="0,100" operation="LTE" value="35"/>

Alarm Duration
Config>gameevents.xml the Value Number/Number is in Seconds
<action_sequence name="alarm_sound">
<property name="loop_duration" value="8" />

Spawn Chances
Config>gameevents.xml the Value Number/Number is in Seconds
<requirement class="RandomRoll">
<property name="value" value="20" />

Spawn Numbers
Config>gameevents.xml the Value Number
<action class="SpawnEntity">
<property name="value" value="20" />
<property name="spawn_count" value="4" />

  
</details>

#

<details>
  <summary>
    <h3>Downloads/Installation Instructions</h3>
  </summary>

+ To install the mod, click , [A20 Download](https://github.com/DarkAoRaidenX/7-days-to-die-mods/raw/main/downloads/CarAlarm-A20.zip) or [A21 Download](https://github.com/DarkAoRaidenX/7-days-to-die-mods/raw/main/downloads/VehicleAlarms-A21.2.0.0.zip) open the file you downloaded with an extraction tool such as [7 Zip](https://www.7-zip.org/). 
  + The folder you extracted should be called `CarAlarm` or `VehicleAlarms-A21.2.0.0`. 
  + Now move that folder to your `Mods` folder in your 7 Days to Die directory, if you do not have one, make one.        
+ Your directory should now look something like this: Mod folder should be only 1 Folder deep.   
```\7 Days To Die\Mods\ModFolderName```
+ A Wrong PathWay: 
```\7 Days To Die\Mods\ExtraFolder\ModFolderName\```    

*Note: Due to the The Fun Pimps changing how mods are loaded, these installation instructions will change soon*

___IMPORTANT: Mods for 7 Days to Die will never come in .exe form, Do not trust random applications.___     

</details>
   

##

<details>
  <summary>
    <h3>Contact Info</h3>
  </summary>
  
  + If you run into any conflicts or need help, you may contact DarkAoRaidenX via discord: [discord](https://discord.gg/UccyzVm5Xq) or DarkAoRaidenX.

</details>


##


<details>
  <summary>
    <h3>Updates</h3>
  </summary>
  
2.00
- Added where there's a chance when the Alarm goes off it will Spawn 4 Zombies. It should scale up with the Gamestage
So it will spawn Normal,Feral,Radiated *Hopefully* around the right time.

- BE WARNED they can spawn during the timer loot. So could have multiple spawns if you cancel the looting and loot again.
-- Trying to find out a way to only go off after the Timer goes away.

</details>


##


<details>
  <summary>
    <h3>Wish List</h3>
  </summary>
  
This list is what I want to be able to do.
+ 
</details>

##

[Back to Mods List](../../main/README.md)