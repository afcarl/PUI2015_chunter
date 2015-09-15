## PUI2015_chunter

### week 1 - set up environment and alias
The environment variable is simply the full path to my PUI2015 folder, which then makes setting the alias easier. using the alias I can just type "pui2015" to switch directly to that folder from any other location.

To set up the environment variable and alias I edited my .bashrc file to include the following two lines:
export PUI2015=/home/clayton/Documents/CUSP/courses_2015/PUI2015
alias pui2015="cd $PUI2015"
As shown in the image here:
![alt text][bashrc_snapshot.png]

Which results in this nice shortcut:
![alt text][alias_commands.png]
