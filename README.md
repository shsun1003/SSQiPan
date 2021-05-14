SSQiPan (猴儿棋盘) -- An AI GO (AI Weiqi, 人工智能围棋) desktop client application written in C#.

(1) Supports most AI Go engines that output GTP protocol, such as KataGo, SAI, Leela Zero, PhoenixGo, GNUGo, etc.

(2) Lets you play or watch games in many combinations, such as AI vs AI, human vs AI or human vs human.

(3) Contains a powerfull game analyzer, which use KataGO analysis feature. Among the freely available AI GO engines, KataGO is one of the strongest. This analyzer can evalute the current during a game, give the winrates for each suggested move or its principal variation (VP). Either the move or VP will displayed on the board. (See attached AI Analyzer.png)

(4) Displays winning rate curves for every stone, letting you observe a good or bad moves immediately.

(5) The installation is simple. Just download the zip file and uncompress it into a folder, then you may play by double clicking SSQiPan.exe. Or, I would recomended, you may creat a shortcut on the desktop. For KataGO engine, some lines in both default_gtp.cfg and analysis.cfg (or whatever you renamed). The most import three lines need to be set to "true"!

  logToStderr = true      # Echo everything output to log file to stderr as well
  logAllRequests = true  # Log all input lines received to the analysis engine.
  logAllResponses = true # Log all lines output to stdout from the analysis engine.


NOTE: The screenshots may not accurately reflect the GUI in the latest versions.
