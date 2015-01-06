#Meowbot Translations
===================

#Translate all messages on the left side of the message type name.

##Example:
	"reboot_now": "Rebooting for maintenance. Maintenance can take around 5-10 minutes. I will auto-join the channel once I'm back online.",
	
You would keep "reboot_incoming" as it is typed but convert the rest of the message starting with "Rebooting for maintenance"

#Do not translate anything surrounded by %'s. These are keys used by the bot to replace with information.

##Example:
```
"joinChannel_proccess": "Joining @%User_Name%'s channel!",
```
  
You would keep %User_Name% but translate the "Joining channel" part of the message.

Commit your changes by changing the file en of the name from en_messages to your language code. This makes it so the bot knows which language the file is for.
