# dankengine-hypetrain
Experimental Hype Train

---Required OBS plugins---

1.) Source Copy - Used to Load The Scenes Easily

https://obsproject.com/forum/resources/source-copy.1261/

2.) Move transition - Used to Move the train cars

https://obsproject.com/forum/resources/move-transition.913/

---Extracting Files---
Unzip them to C:/Train
There's probably a better way of doing this, or a better place to put these files, but I have no idea what I'm doing.

---Configuring OBS---
Use Source Copy to import Train.json, You can copy the filters from the "Live Play - sitting" scene to wherever you want to put the train, BUT you'll have to make sure it's reflected/replaced in each of the "Train" actions in Streamer.bot

Configuration of Streamer.bot-
1. Import the HypeTrain_StreamerbotExport JSON file into Streamer.bot
2. Go to Settings > Events > Hype Train
Set the settings as follows.

Start
Action: Train1

Level Up
Level: 
Generic : Action - Train1
Level 1 : Action - <None>
Level 2 : Action - Train2
Level 3 : Action - Train3
Level 4 : Action - Train4
Level 5 : Action - Train5

Progression
Action: <None>

Finish
Action: TrainClear
