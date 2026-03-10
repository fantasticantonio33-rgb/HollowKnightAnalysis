Hollow Knight - Player Completion Analysis
An analysis of Steam achievement data for Hollow Knight to identify where and why players abandon the game, built using Python, Pandas, and Matplotlib.
The Question
Where do most players quit Hollow Knight, and is it because the game is too hard or because it gives you almost no direction?
Hypothesis
The biggest player drop-off occurs before mechanical difficulty becomes a factor, driven by the game's lack of guidance at the start. A second drop-off was expected around the first major skill checks, Mantis Lords and Soul Master.
Data Source
Steam Global Achievement API, pulled live for Hollow Knight (App ID: 367520). Free and publicly accessible, no API key required.
What I Found

30% of players never earned a single achievement, the game lost them before it even started
Player drop-off happens in waves, not a steady decline
Mantis Lords and Soul Master landed exactly where predicted for the second drop-off
The Pantheons filter out almost everyone, only 4% of players ever reach Steel Soul
A portion of players somehow progressed deep into the game without ever picking up a map, which is either a speedrunning thing or an achievement quirk worth investigating further

Tools Used

Python
Pandas
Matplotlib
Steam Web API

Next Steps
Follow-up project using individual player data to confirm whether completing optional hard content like Path of Pain predicts Pantheon 5 completion.
