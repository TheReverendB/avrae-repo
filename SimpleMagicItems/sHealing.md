An alias for using the Staff of Healing.  Creates the counter, casts the spells and uses the counter to keep track.
 
__Using the Staff:__
 
Cure Wounds - `!sHealing cure [charges used] [-t target]`
 
Lesser Restoration - `!sHealing lesser [-t target]`
 
Mass Cure Wounds - `!sHealing mass [-t target]`
 
Recharging - `!sHealing recharge` (In case you are adventuring when dawn strikes.)
 
 
Support the work I do with [Ko-Fi](https://ko-fi.com/thereverendb)
 
The code behind these aliases will be posted as available on my [Github](https://github.com/TheReverendB/avrae-aliases)
 
This alias will create a counter that resets on a Long Rest.  If you want it to only manually reset, delete your counter ( `!cc delete "Staff of Healing"` ) and create a new counter before using this alias again as follows: `!cc create "Staff of Healing" -min 0 -max 10 -resetby 1d6+4 -type bubble`