## __This alias only works in combat.__

It can be used to roll stealth checks for targeted combatants.
It takes into account any passive effect adding check bonus or advantage to Dexterity or Stealth.

`!hide adv` will roll a stealth check with advantage to hide.
It defaults to your character without any other targets.

Target specific arguments are possible, as is targeting a group:
`!hide -t GO1|dis -t "Group of Wolves| -b 10"   adv`
This will roll stealth checks for all the wolves at advantage and with a +10 bonus.
GO1 rolls a straight check (adv+dis)


### Since the attack advantage granted by the Invisible condition is subject to conditions, it isn't added by default.

You can create an svar to make the alias grant advantage to all attacks like so:
`!svar hideAliasAdvantage yes`

If you want to return to not applying attack advantage, delete the svar:
`!svar delete hideAliasAdvantage`

The code behind this alias is available on my [Github](https://github.com/TheReverendB/avrae-aliases)

Support the work I do with [Ko-Fi](https://ko-fi.com/thereverendb)