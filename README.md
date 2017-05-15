 So one of the admins on our community has been playing with the editor for a bit now.  Hes gotten real good and his
 attention to detail is amazing.

He made this for our server, and it was so nice, i asked him if he would make a oval track around the racetrack.
He kindly allowed me to share it here with everyone to use.  The only condition we ask, is please leave the
"Elite SLK" made of tires in the middle of the track :)

ALL CREDIT GOES TO OBDURATE, admin on Elite SLK gaming community.

Here are some pics

http://tinypic.com/r/x6dls3/9

http://tinypic.com/r/11gt9g6/9

It is Located South West of Chernarus. About 500m North West of Pavlovo.

You'll need epoch and overwatch for this.

There are some ambient sounds around the track, if you dont like it, search in the code for sounds and delete the block of code associated with it.

Also.  We had custom billboards at the entrance of the racetrack.  They are commented out in this script im posting (at the bottom of the script).  You can make your own texture and uncomment them and change the paths 

Installation:

In your server PBO, place the file in a folder called "objects".  If you don't have one, create the folder. 

In your server_functions.sqf, find this line
server_sendToClient = compile preprocessFileLineNumbers "\z\addons\dayz_server\compile\server_sendToClient.sqf"; 

Add this bellow
execVM "\z\addons\dayz_server\objects\racetrack.sqf"; 


Re-Pack your server PBO and enjoy.
