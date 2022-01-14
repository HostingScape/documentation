# Lag Types
TPS - Server Lag
TPS stands for Ticks Per Second. It is also the only lag type a server owner has direct control over. The guide above is exclusively intended to improve TPS.

A server processes all tasks at a rate of 20 TPS. Tasks like mob movement, crop growth, and player interactions with blocks need to be ticked by the server to function properly. A TPS below 20 means the server is running behind and must skip tasks in order to keep important tasks on time. Significant TPS loss usually presents itself with minor annoyances like intermittent mob freezing and block break resets. Severe cases could result in server-wide freezes or even crashes.

TPS Ratings
20.0 = Flawless - Well done.
19.95-19.99 = Great - Unnoticeable TPS loss. Most servers live here.
18.5-19.94 = Fair - Maybe some annoyances, but nothing game-ruining.
16.0-18.4 = Poor - You definitely need to fix this if this is your average.
<16.0 = Unplayable...


Ping - Connection Lag
Ping (aka latency) reflects how long (in milliseconds) data takes to process and travel between the client and server host. The further a client is geographically separated from the server, the longer this transfer might take. Other common influences on ping are congested or slow connections.

As a server owner (assuming you have a choice) you should host your server in a region where you prefer to have your player base or one that appeases a broad range of players.

Example: Eastern US is good for most of the US, CA, and UK, while Central US is more ideal for just US and CA.

Ping Ratings
1-90 = Great!
91-179 = Good - Maybe a slight disadvantage in PvP.
180-299 = Poor - Regular lag while interacting with blocks/players/entities.
300-499 = Bad - Nearly unplayable.
500+ = Assuming your bandwidth is solid, it's time to find a server closer to you.


FPS - Client Lag
Do not confuse TPS with FPS (Frames Per Second). FPS reflects a client's ability to process and display what the game/server wants to render. FPS is 100% client side and has nothing to do with server performance.

The only thing a server can do to help FPS is cut server features so dinosaur PCs can keep up, but even that is unlikely to make a big difference. Instead of reducing server features, recommend a popular client mod called Optifine to players.

FPS Ratings
Note: These rates assume your standing average in a non-graphic-intense location.
60+ = Perfect - Anything over 60 FPS is overkill for Minecraft. Consider capping FPS below 80 to avoid unnecessary stress on hardware.
40-59 = Great - Should have no issues.
25-39 = Good - Occasional rendering lag. Issues if you enter graphic-intense areas.
15-24 = Poor - Constant rendering glitches. Probably freeze in GI area.
1-10 = Bad - Client should significantly reduce graphic settings.


Timing Reports
Invest time in watching this informative video guide on the Timings program. The video breaks down Timings v1(Spigot) and v2(Paper). The video length is intimidating, but any serious server owner should know how to identity their server's issues.
https://youtu.be/T4J0A9l7bfQ