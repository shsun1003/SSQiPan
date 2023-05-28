****************************************************************************************************
NOTE: This application has been totally re-written with much better logic, also the app name
has been changed. All you need is to download and unzip file "SSShouTan 23.05.28.512.zip".

All screenshots may look somewhat different from the newly rewritten application. However, they
should functionally the same.

If you have any questions or you need some assistances, plesase go to the Discussions or just email
to me
****************************************************************************************************

SSShouTab (SS 手谈) -- An "AI GO" (AI Weiqi, 人工智能围棋) desktop client application written in C#, running on 64-bit Windows 8 and later.

(1) Supports most AI Go engines that output GTP protocol, such as KataGo, SAI (a new Leela Zero variation), Leela Zero, PhoenixGo, GNUGo, etc (See the attached Game Samples screenshots).

(2) Lets you play or watch games in many combinations, such as AI vs AI, human vs AI or human vs human.

(3) Contains a powerfull game analyzer, which employs KataGO analysis feature. Among the freely available AI GO engines, KataGO is one of the strongest. This analyzer can evalute the current during a game, give the winrates for each suggested move or its principal variation (VP). Either the move or VP will displayed on the board. (See attached AI Analyzer.png)

(4) Displays winning rate curves for every stone, letting you observe a good or bad moves immediately (See attached Winrate Curves.png).

(5) The installation is simple. Just download the zip file and uncompress its content into a folder, then you may play by double-clicking "SSShouTan.exe". Or, I would recomend, you may create a shortcut on the desktop. For the KataGO engine (which is one of the strongest AI GO freely avaiable), some lines in both default_gtp.cfg and analysis.cfg (or whatever you renamed). The most import four lines need to be uncommented and set to "true" as below (See attached KataGO Config.png).

  logToStderr = true
  
  logAllRequests = true
  
  logAllResponses = true
  
  ogsChatToStderr = true
  
(6) Requires 64-bit Windows 8 and later, with .NET Framework 4 and above. A good video card is recommended, but not required, depending on the AI GO engines you use. For example, KataGO, LZ and SAI all have a "CPU only" edition.


NOTE: The screenshots may not accurately reflect the GUI in the later versions.
