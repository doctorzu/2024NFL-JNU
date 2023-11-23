# 2024NFL-JNU
NFL 2024 Big Data, By Zhu

This is a Term project of Jiangnan University. We are totally green hands in Big Data
SO JUST KIDDING, never treat it seriously

if you r willing to providing us with suggestions, please contact us with

e-mail: 1193210215@stu.jiangnan.edu.cn

qq: 3536607431

__________________________________________________________________________________________________________________________
Please organize files as follows:
- 2024NFL-JNU
  - LICENSE
  - README.md
  - demo.py
  - test.txt
  - .idea
    - .gitignore
    - 2024NFL-JNU.iml
    - misc.xml
    - modules.xml
    - vcs.xml
    - inspectionProfiles
      - profiles_settings.xml
  - Code
    - test.py
    - test.ipynb
  - Datasets
    - games.csv
    - players.csv
    - plays.csv
    - tackles.csv
    - tracking_week_1.csv
    - tracking_week_2.csv
    - tracking_week_3.csv
    - tracking_week_4.csv
    - tracking_week_5.csv
    - tracking_week_6.csv
    - tracking_week_7.csv
    - tracking_week_8.csv
    - tracking_week_9.csv

__________________________________________________________________________________________________________________________
Goal: create metrics that assign value to elements of tackling. 

Examples to consider:

• Predictions of tackle time, probability, and/or location

• Tackle range: angle of pursuit, speed and acceleration, closing speed

• Player evaluation (e.g, yards saved, tackle value, missed tackles)

• Credit assignment (e.g, one player makes a tackle because of another players, blocks shed, area of influence)

• Tackle type (solo vs gang, open field vs in the trenches, etc)

• Team and player roles and responsibilities (setting the edge, filling gaps, etc)

————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————————
数据集信息：

games.csv：比赛信息，关键变量：gameId

plays.csv：比赛的比赛级别信息，关键变量：gameId和playId。

players.csv：球员级别信息，关键变量：nflId。

tackles.csv：每场比赛和比赛的球员级别的铲球信息，关键变量：gameId、playId和nflId。

tracking_week_[week].csv：包含第[week]周的球员追踪数据，gameId、playId和nflId。

