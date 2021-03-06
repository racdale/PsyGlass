PsyGlass: An Open-Source Framework for Implementing Google Glass in Research Settings

Before implementing, we recommend reading through the files to familiarize yourself with the code.

Be sure to change the server string ("public static final String ADDRESS" variable in "GameActivity.java" file) to target server address. Please note that server-connection functionalities may be limited when testing from Android Studio. We recommend publishing the signed APK with the target server address and uploading the app to your Glass to fully test server connection.

Transfer the following files and folders to the target server location before running:
		data.html
		experiment.html
		index.html	
		"resources" folder
		"data" folder (should be given read, write, and execute permissions)

Additional "wrappers" available to transform the experimenter console. Relevant files are available in folders:
		Lexical Decision Task
			Modifies the experimenter console to include a "Decissify" 
			button that will update connected Glass devices with words 
			from a list of words and nonwords. Lists may be modified 
			on the associated .js file.
		
For more, see "PsyGlass: Capitalizing on Google Glass for Naturalistic Data Collection" (Paxton, Rodriguez, & Dale, in press, Behavior Research Methods).

For information on purchasing Glass for your research team, email glass-edu(at)google(dot)com.

Written by K. Rodriguez, A. Paxton, & R. Dale
Created on 13 October 2014
Last modified on 8 April 2015