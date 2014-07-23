ToonTracker -- An IRC Bot
-----------------------------------------
An mIRC scripted bot named ToonTracker used for various purposes

###About
This bot's primary ability is to read, store, and generally "track" invasions in various community servers, including, but not limited to, Toontown Rewritten (TTR) and Toontown Infinite (TTI). For TTI, it tends to base around user-reports, relying on their service to know when invasions are starting and ending, however with TTR, it uses http://toonhq.org/ 's invasion API, which is an expanded version of TTR's built-in Invasion API.

ToonTracker also has the ability to check if the TTR's game and account servers are down (to be added to GitHub), using the Login API/Flow that's used by the launcher. Using this method does have an advantage -- instead of having to store and check every gameserver IP that is used and then just checking the website to see if it's up, using the Login API can tell you if the Account Server is up, and if it is, then check the gameserver IP that's provided by it. 

Among this, there are some "easter eggs" scattered here and there, just for fun. :)
I'll be adding more code files later, of course -- the current one is just for TTR invasion checking! Have fun, and if you see something that could be improved upon or have a brilliant idea, feel free to submit a pull request! 

###Help
Oh, also... at any time if you need help, or just want to find a certain command, just say "TT~help" in the chatroom. It will (soon) bring up some documentation to get you going. In the meantime, just go with the flow!