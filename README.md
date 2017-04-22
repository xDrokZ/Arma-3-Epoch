# Arma-3-Epoch

1. Put a3_epoch_autolockpicker.pbo in ur Serverside Addon folder

2. Open missionfile and add the custom to your addon folder or create it
3. In initplayerlocal.sqf add:

call compileFinal preprocessFileLineNumbers "addons\custom\AutoLockPicker.sqf";	systemchat("Safe and Vehicle Lockpick enabled");

4. Repack missionfile and ur done
