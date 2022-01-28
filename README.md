# NoMoreSway
Removing Weapon Sway in ADS in Titanfall 2
[NoMoreSway_by_Avalar v1.4]

[LastRelease](https://github.com/Strykus/NoMoreSway/releases)

Want to ask me something? feel free to dm in my discord: Avalar#2742

v1.0 - Working as intended, but values not affecting regular Wingman for some reasons.

v1.1 - Regular Wingman now affected by values.
- Values was optimized and was removed parts of the code that mod not affecting. Now it have better compability with other mods that use changing View Models.
- Was made separate txt files("mp_weapons_fov_sw.txt") that globaly change settings for every weapon.
- Was added separate txt files for weapons: Hemlock - "mp_hemlok_fov_sw.txt"(due to fix of his Iron Sight was not on the centre of the screen); 
Charge Rifle - "mp_defender_fov_sw.txt" (removed Zoomed Sway values because moddel start flying around when you try to moove in ADS)
Wingman Elite - "mp_wingman_e_sw.txt" and Regular Wingman - "mp_wingman_e_sw.txt" (because they working normally only when file was made for each weapon)
- You can change values of "viewmodel_offset_hip" "z x y" for your custom hipfire viewmodel.
- You can change values of "zoom_fov" "field of view you want to use" to chagne field of view when using ADS and you can change for the each scope that game have in "mp_weapons_fov_sw.txt" in "Mods" section.

v1.2 - Removed ability to change zoom_fov for each weapon scope because it causing broken scope on custom servers for now.
- moved EPG, Cold War, SMR, MGL and Softball now sending request to setting in mp_defender_fov_sw.txt file, because ADS was broken for those weapons.
- 
v1.3 
- Add back Ability to change zoom_fov for each weapon scope depends on weapon type - mp_alternator/mp_assault/mp_lmg/mp_spitfire/mp_g2/mp_smg ect.
- Fixed Hemlock scopes was not showed correctly

v1.4
- Fixed ADS scope shifts away from centre of the screen, now scope following weapon spread

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Notes: Northstar requires to making this mod work: https://github.com/R2Northstar/Northstar
     
Install mod by going to Titanfall 2 root directory >>> "R2Northstar" and drop mod folder named "NoMoreSway" into "mods" folder.
