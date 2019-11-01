# tomkeys
A plugin for the [OpenOSRS](https://openosrs.com) client that allows you to bind various actions to hotkeys. Shoutout to [Ganom](https://github.com/Ganom) for sharing code in his [plugins repository](https://github.com/Ganom/ExternalPlugins), which made development easier.


## Syntax for Hotkey Scripts
Scripts bound to hotkeys use the following commands:

- **[ITEM:ID] :** Click on an inventory item the specified item ID.Example : **[ITEM:1234]
- **[ITEM:ID,ID...] :** Click on multiple inventory items, using a list of item IDs separated by commas. Example : **[ITEM:1234,420,6969]
- **[SPELL:SPELL_NAME] :** Cast a spell with the specified name. Example : **[SPELL:ICE_BARRAGE]** 
- **[SPEC:NUMBER] :** Activate special attack the specified number of times. This will usually be **[SPEC:1]**. The only time **[SPEC:2]** should be used is for activating the special attack of the [Granite maul(or)](https://oldschool.runescape.wiki/w/Granite_maul_(or)) twice.
- **[PRAY:PRAYER_NAME] :** Toggle the specified prayer on or off. Examples : **[PRAY:PIETY], [PRAY:PIETY,PROTECT_FROM_MELEE]**
- **[PRAYON:PRAYER_NAME] :** Activate the specified prayer if it is off. If it is already on, do nothing. Example : **[PRAYON:PIETY]**
- **[PRAYOFF:PRAYER_NAME] :** Deactivate the specified prayer if it is on. If it is already off do nothing. Example : **[PRAYOFF:PIETY]
- **[POT:POTION_NAME] :** Find the specified potion if it's in your inventory and click on it. This prioritizes the potions with the lowest number of doses. Example : **[POT:SUPER_RESTORE]**
- **[TAB:TAB NAME] :** Press the hotkey to switch to switch to the specified tab. Example: **[TAB:INVENTORY]**

**ITEM**, **SPELL**, **SPEC**, **PRAY**, and **POT** will all switch to the correct tab automatically. 
## **Example Script** 
```
[ITEM:13652,1725]
[PRAYON:INCREDIBLE_REFLEXES]
[PRAYON:ULTIMATE_STRENGTH]
[SPEC:1]
[TAB:INVENTORY]
```
A demonstration of the plugin in action and a more comprehensive tutorial for usage will be available in the future. 

## Upcoming Features:
- Quick prayer hotkey.
- Presets for groups of scripts, functioning similarly to the inventory setups plugin in the OpenOSRS client.

## This is GitHub, where's the source?
While I am making this plugin freely available, I am not planning on sharing the soucre code as of right now. I'm just using GitHub for the free file hosting. Sorry. 
I will release the source when the code looks less embarrassing.

## Other Stuff
This plugin will only contain features that perform automated mouse/keyboard actions in response to pressed hotkeys.

I will **not** be implementing anything using menu entries or similar methods.

I will **not** be implementing anything that performs actions triggered by events in game, such as automatically eating when low HP or automatically switching prayers based on your opponent's attack style.

I am choosing not to add those or anything similar for numerous reasons. 

Feel free to request new features if they perform mouse/keyboard actions in response to pressed hotkeys.

I am available via Discord if you want to contact me, **Tom C#2114**.

## Support Me (pls)
The plugin will always be available for free, but if you would like to send some money my way I have recently created a Patreon. I am a broke student as of right now. Additionally, my neighbor's goldfish suffers from leukemia, and donations would be able to help pay for treatment.

https://www.patreon.com/tomcosrs
