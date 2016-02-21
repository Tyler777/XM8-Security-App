# XM8-Security-App<br>
XM8 Security Application for use with XM8Apps by Shix!<br>

# Install Instructions<br>
Add ExileSecurity Folder too "xm8Apps\"<br>

Add this to your XM8Apps_Init.sqf<br>


//App 1<br>
_app1Text = "XM8Security";<br>
_app1Logo = "xm8Apps\ExileSecurity\Images\ExileSecurity.paa";<br>
app1_action = {<br>
[] spawn {call ExileSecurity}; <br>
};<br>


Add this to your ini.sqf in the root of your mission.map<br>

//Exile Security XM8<br>
[] execVm "xm8Apps\ExileSecurity\Init.sqf";	<br>
