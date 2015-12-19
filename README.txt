Author: Amanda Szampias
Game: Unreal Tournament 1999
Date: October 3, 2014

SayMessagePlus and DeathMessagePlus are info classes used by UT HUD to draw messages onto the screen. Both classes belong to BotPack.u.

ACE doesn't do integrity checks on property alterations, only function tampering. I can mess with how UT looks but not the mechanics. Some admins will install AntiTweak to block certain illicit SET commands. Commands that can make walls transparent, flags that glow and expand, radar player lightning techniques etc. I tested both of my custom SET commands on my server and Chamberly's server, both work with ACE and AntiTweak V 5.2 installed. My custom exec SET commands only work for one session. They must be called upon each time UT is opened. They are not permanent.

HOW TO RUN:

1. Place DeathMessagePlus and SayMessagePlus in the System folder.
2. Run UT and open the console before joining a server.
3. Type exec DeathMessagePlus. Type exec SayMessagePlus.
4. You will notice that all SAY and red Deathmessages are hidden from your chat area.
5. Close UT and restart to return to original settings. 

USED FOR:

1. Ignoring spammers during competitive leagues. 
2. Wanting peace and quiet away from players using chatbox.

HOW IT WORKS:

UT99 does not render black text thus making it transparent.