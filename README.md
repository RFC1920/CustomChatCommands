# CustomChatCommands
This is a fork of the CustomChatCommands plugin at https://oxidemod.org/plugins/customchatcommands.2307/.  It is hoped to be temporary.

Here, we have added the ability to create a command alias, e.g. to alias /r to /remove, etc.  This can be applied to any chat command.

The relevant config changes are:

```
    {
      "Command": "skinbox",
      "Messages": [],
      "Permission": "",
      "ConsoleCmd": null,
      "UserID": 0,
      "Broadcast": false,
      "RconCmd": null,
      "Cooldown": 0.0,
      "MaxUses": 0,
      "Alias": "skin"
    }
```

For each command section, add at least "Alias": "".  If you wish to alias a command, add the alias.
For the example above, the /skin command becomes an alias for /skinbox.

See the original plugin for more information about the plugin in general.
