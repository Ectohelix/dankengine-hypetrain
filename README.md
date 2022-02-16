# dankengine-hypetrain
Experimental Hype Train

---Required OBS plugins---
1.) Source Copy - Used to Load The Scenes Easily
2.) Move transition - Used to Move the train cars

---Configuring OBS---
Once you've used Source Copy to import Train.json, You can copy the filters from the "Live Play - sitting" scene to wherever you want to put the train, but you'll have to make sure it's reflected/replaced in each of the Train scenes in Streamer.bot

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
