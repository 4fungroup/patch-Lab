# "patch" SmartAI Lab Information

- It's SmartAI project, original written for Trinity Core. https://github.com/TrinityCore/TrinityCore
- Scripting ONLY creatures SPELLS,EMOTES,TEXTS !!!( for now ).
- All scripts for Cataclysm 4.3.4, Mists of Pandaria 5.4.7, Warlords of Draenor 6.2.3, Legion 7.3.5 and Battle for Azeroth 8.x.x

anyway this can help you enjoy this game with perfect scripted monsters in the world. 
## INSTALL MANUAL:
- 1) backup your smart_script folder from Database
- 2) go to patch-xxxxxx xxx folder ( choose from Cata to Legion, what your server support)
- 3) run patch_Installer.bat, follow instructions
- 4) go to your smart_script folder and open it in Notepad++ programm
- 5) delete all upperdata (with create table and etc) to tables data 
( where "insert  into `smart_scripts`(`entryorguid`,`source_type`,`id`,`link`,`event_type`,`event_phase_mask`,`event_chance`,`event_flags`,`event_param1`,`event_param2`,`event_param3`,`event_param4`,`event_param_string`,`action_type`,`action_param1`,`action_param2`,`action_param3`,`action_param4`,`action_param5`,`action_param6`,`target_type`,`target_param1`,`target_param2`,`target_param3`,`target_x`,`target_y`,`target_z`,`target_o`,`comment`) values .... )
- 6) change "insert" to "replace" and save file
- 7) apply smart_script.sql ( backuped data and edited) into your database ( using SQLyog for example )
- 8) ren your server and have fun with most playeble world.
P>S> don't forget set mmaps ON in worldserver.conf


## DONATE INFO:
- If you wanna help project you can use one of this ways:
- a) Sberbank Card (RUB)\Карта Сбербанка (РУБ) : 4276 6000 1087 7237
- b) PayPal : https://www.paypal.me/coolerSAI/

## DONATE THANKS:
- zealot2007 (in $), - Otaku STL (in $), - JetixKID_ru (in RUB), - JoshTG (in £), - kittySmile (in RUB).

![bfalogo](https://cdn1.radikalno.ru/uploads/2019/6/3/68a1d7b2bc19225aa3f7f4c204911476-full.jpg)


## BFACore Open Source MMO Framework (master = 8.0.1.28153) 
https://github.com/BFASource/BFACoreN

