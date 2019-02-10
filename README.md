# Paths2019
A repository for editing and storing paths for the 2019 FRC season.

Uses software found at https://github.com/wpilibsuite/PathWeaver

Meant for use with code from team1306/Robot2019 and team1306/Vision2019

<h1>Naming Conventions</h1>
<h2>General Format</h2>
Paths should be named by origin to desination using capital case. For example, going from the left loading station to the nearest port on the cargo ship (front left) should be called "LeftLoadingToFrontLeftCargo"
<h2>Location Names</h2>
![Refer to fieldmap.png](www.github.com/team1306/Paths2019/fieldmap.png)

Field names are oriented from the view of the drive team. Since the field is symetrical, names must be preceded either with "Left", "Right", or (in one case) "Center". The names of each position is listed below, mapping to numbers on the image.

0 - LoadingStation

1 - Depo

2 - CargoFront

3 - CargoNear

4 - CargoMid

5 - CargoFar

6 - RocketNear

7 - RocketMid

8 - RocketFar

9 - Hab

10 - CenterHab. Techinically part of 9, but since its the only place to have be center, it gets its own number. Does not need "left" or "right" in front.