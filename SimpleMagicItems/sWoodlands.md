An alias for using the Staff of the Woodlands.
 
`!sWoodlands "<spell>" [cast arguments] [-i]`. 
 
Creates the counter, casts the spell and uses the counter to keep track. Using `-i`, the staff can be used without expending the charge.
 
You only need to type a unique part of the spell name in order to cast the spell, using quotes for multi-word spells.
Examples of how to use the staff:
 
Barkskin - `!sWoodlands bark [-t target]`
Speak with Animals - `!sWoodlands "with animal"`
Locate Animals or Plants - `!sWoodlands locate`
Wall of Thorns - `!sWoodlands wall [-t target] [-t another] [-dc 14]`
Pass without Trace - `!sWoodlands pass`
Tree Form - `!sWoodlands tree`
Syntax and spells - `!sWoodlands ?` 
 
 
### This alias will create a counter and use charges based on your character sheet version.
The default version in Avrae currently is 2024.
The 2024 Staff of the Woodlands has a different total uses, reset and cost for casting Pass without Trace.
If your counter has the wrong amount of charges you can delete it, change your settings and run the alias again or edit the counter (see `!help cc edit`).
 
Otherwise:
`!csettings version 2014` will set your character sheet version to 2014 (you can also set this to 2024 in the same way)
`!cc delete woodlands` will delete your counter
`!sWoodlands` will create a new counter for your character
 
Alias written by @Velglarn#4688 Thanks so much for sharing!
 
The code behind these aliases will be posted as available on my [Github](https://github.com/TheReverendB/avrae-aliases)