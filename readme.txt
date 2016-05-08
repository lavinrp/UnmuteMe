“Fix” for ACRE2 mute error
Unmutes TS users in two situations:
1.	Plugin user enters channel
a.	All users in channel are unmuted
2.	TS user (not plugin user) changes channel
a.	Only unmutes user who changed channel

Built using TS3 pluginsdk

