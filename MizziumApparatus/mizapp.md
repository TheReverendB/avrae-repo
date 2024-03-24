An alias for using the Mizzium Apparatus.  This will make the Arcana roll and cast the spell all in one go.

**Now with partial spell name matching!**
Keep in mind you are matching spells against all official 5e spells so you will still need to be pretty specific.  Also important to use double quotes around the spell name - especially if there is an apostrophe in the spell name.

`!mizapp "spell name" [spell args]`

If you need to add modifiers to your Arcana roll, you can add them after an `*` in the arguments like this:

`!mizapp "fire bolt" dis -t go1 * adv -b 1d4 `

This will cast "fire bolt" with disadvantage to hit go1, but with advantage and a bonus 1d4 on your Arcana roll to use the Mizzium Apparatus.

Support the work I do with [Ko-Fi](https://ko-fi.com/thereverendb)


added `-i` support
added support for `-mc` argument for the Arcana check
also supports using `guidance` as an argument similar to using the snippet to add 1d4 bonus to your Arcana roll.
supports Mark of Making +1d4 for Artisan's Intuition automatically, as well as Vedalkin's Tireless Precision if you add `precision` in your arcana args (after the `*`)

If official spells are missing from the list, find me in the [Avrae Development Server](https://discord.gg/Wrr38KuN) and let me know.

You can now add homebrew spells by making an `svar` or `uvar` named `MAHomebrew` following this example:
```json
!svar MAHomebrew {
        "0": ["vicious mockeries"],
        "1": ["which bolt?"],
        "2": [],
        "3": ["wind break", "fireballz"],
        "4": ["aura of stank"],
        "8": ["dominate momster"]
  }```
You can use an empty list or remove the level completely if you have no spells for a level.
Spell names should be all lowercase and server homebrew will take priority over personal homebrew.