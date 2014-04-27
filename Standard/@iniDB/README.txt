iniDB - A simple server-side database extension using INI files (and more)

----------------------------------------------------------------------------------------------

Author: 
	SicSemperTyrannis
	
Support: 
	http://raiderbattalion.enjin.com/

How to use:
	To use "iniDB" in your mission, install the extension in your ARMA2 or ARMA3 directory by copying the entire "@inidb" folder included in the download to your root directory. 
	Don't forget to copy over over or create the /db/ folder.
		It should look like: /Arma 3/@inidb/iniDB.dll
		It should look like: /Arma 3/@inidb/db/
		It should look like: /Arma 3/@inidb/Addons/iniDB.pbo
	
	Then in your mission init.sqf, somewhere before you want to use the functions do this:
		call compile preProcessFile "\iniDB\init.sqf";

	It should be noted that when you install the @inidb folder you can delete the /examples/ directory from there if you please, they serve no purpose in that folder.

	You have permission to use, upload or otherwise distribute this as please, but don't hold me responsible for anything.

----------------------------------------------------------------------------------------------

CHANGELOG

13-March-2013
	- Module
		- Initial Release
	- init.sqf
		- Initial Release