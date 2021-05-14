SSQiPan (猴儿棋盘) -- An AI GO (AI Weiqi, 人工智能围棋) desktop client application written in C#.

(1) Supports most AI Go engines that output GTP protocol, such as KataGo, SAI, Leela Zero, PhoenixGo, GNUGo, etc (See the attached Game Samples screenshots).

(2) Lets you play or watch games in many combinations, such as AI vs AI, human vs AI or human vs human.

(3) Contains a powerfull game analyzer, which use KataGO analysis feature. Among the freely available AI GO engines, KataGO is one of the strongest. This analyzer can evalute the current during a game, give the winrates for each suggested move or its principal variation (VP). Either the move or VP will displayed on the board. (See attached AI Analyzer.png)

(4) Displays winning rate curves for every stone, letting you observe a good or bad moves immediately (See attached Winrate Curves.png).

(5) The installation is simple. Just download the zip file and uncompress its content into a folder, then you may play by double-clicking "SSQiPan.exe". Or, I would recomend, you may create a shortcut on the desktop. For the KataGO engine (which is one of the strongest AI GO freely avaiable), some lines in both default_gtp.cfg and analysis.cfg (or whatever you renamed). The most import three lines need to be set to "true" as below.

  logToStderr = true
  
  logAllRequests = true
  
  logAllResponses = true


NOTE: The screenshots may not accurately reflect the GUI in the later versions.
