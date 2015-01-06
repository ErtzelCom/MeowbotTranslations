#Meowbot Translations
===================

#Translate all messages on the left side of the message type name.

##Example:
	"reboot_now": "Rebooting for maintenance. Maintenance can take around 5-10 minutes. I will auto-join the channel once I'm back online.",

	
You would keep "reboot_incoming" as it is typed but convert the rest of the message starting with "Rebooting for maintenance"

#Do not translate anything surrounded by %'s. These are keys used by the bot to replace with information.

##Example:
	"joinChannel_proccess": "Joining @%User_Name%'s channel!",
  
You would keep %User_Name% but translate the "Joining channel" part of the message.

Commit your changes by changing the file en of the name from en_messages to your language code. This makes it so the bot knows which language the file is for.

To submit your translations and updates, do a pull request on this rep and submit your changes via the pull request for me to look over and bring to the main version. Change the file name from en_messages to replace "en" with your language code that can be found here: http://msdn.microsoft.com/en-us/library/ms533052%28v=vs.85%29.aspx


######Note: Please do not remove the opening and closing quotes or the comma after each closing quote. These are needed for when the file is converted back to json for the bot. Also, if any message requires quotes in it, you must type them as \" like it shows in the English version.
