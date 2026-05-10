***** THE APPLICATION NAME HAS BEEN OFFICIALLY CHANGED TO "SS Gobot" *****

****************************************************************************************************
If you have any questions or you need some assistances, plesase go to the Discussions or just email
to me. 在讨论区，大家可以用英文或中文同我交流。
****************************************************************************************************

SS Gobot -- An "AI GO" (AI Weiqi, 人工智能围棋) desktop client application written in C#, running on 64-bit Windows 10 or later, with Microsoft .NET 8 runtime installed.

(1) Supports most AI Go engines that output GTP protocol, such as KataGo, SAI (a new Leela Zero variation), Leela Zero, PhoenixGo, even GNUGo if you're still using it, etc.

(2) Lets you play or watch games in many combinations, such as AI vs AI, human vs AI or human vs human. A remote play feature is under construction.

(3) Supports server-less remote peer-to-peer play. You can share your computer's IP address and port number with a friend, and then you both can play together. This feature is still being matured, so please report any issues or suggestions. However, how to set up a port through firewalls is beyond my scope.

(4) Contains a powerfull game analyzer, which employs KataGO analysis feature. Among the freely available AI GO engines, KataGO is one of the strongest. This analyzer can evalute the current during a game, give the winrates for each suggested move or its principal variation (VP). Either the move or VP will displayed on the board. (See attached AI Analyzer.png)

(5) Displays winning rate curves for every move, letting you observe a good or bad moves immediately.

(6) The installation is simple. Just download the zip file and uncompress its content into a folder, then you may play by double-clicking "SSGobot.exe". Or, I would recomend, you may create a shortcut on the desktop.

(7) For KataGO engine (which is one of the strongest AI engine avaiable for free), some lines in default_gtp.cfg (or whatever you renamed) need to be modified. Most importly, four lines must be uncommented and set to "true" as below.

		logToStderr = true
  		logAllRequests = true
  		logAllResponses = true
  		ogsChatToStderr = true
  
(8) Requires 64-bit Windows 10 and later, with .NET 8 and above. A good video card is recommended, but not required, depending on the AI GO engines you use. For example, KataGO, LZ and SAI all have a "CPU only" edition.

(9) Support a few color themes and also lets you create your own board images by saving square png image files in the "\Resources" folder and then select in the Setting dialog box.



