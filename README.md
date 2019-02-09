# Obtaining GitHub-repo-stats-using-curl-command-in-Linux-Terminal

How to install Linux Terminal on windows 10: 
1.	Turn windows features on / off.
2.	Check Windows subsystem for linux.
3.	Restart.
4.	Open Microsoft Store
5.	Search Ubuntu
6.	Install.
7.	Create username/password (hidden when you type)
8.	That’s it!
9.	Note: all the Windows files are in the directory: /mnt/c

How to download stats of github repository using curl and github api?
1.	Install curl: sudo apt install curl
2.	See screenshot.png. 
3.	Analyse the .json file (basically a list of dictionaries) . See jsonReader.py.
4.	Resource: https://developer.github.com/v3/repos/statistics/#get-the-last-year-of-commit-activity-data
5.	Note: 
GET /repos/:owner/:repo/stats/commit_activity
Means: https://api.github.com/repos/d3/d3/stats/commit_activity
Where you replace :owner and :repo with the person you want to look up. 
