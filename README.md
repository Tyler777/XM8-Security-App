# XM8-Security-App
XM8 Security Application for use with XM8Apps by Shix!

# Install Instructions
Add ExileSecurity Folder too "xm8Apps\"

Add this to your XM8Apps_Init.sqf


//App 1
_app1Text = "XM8Security";
_app1Logo = "xm8Apps\ExileSecurity\Images\ExileSecurity.paa";
app1_action = {
[] spawn {call ExileSecurity}; 
};


Add this to your ini.sqf in the root of your mission.map

//Exile Security XM8
[] execVm "xm8Apps\ExileSecurity\Init.sqf";	
