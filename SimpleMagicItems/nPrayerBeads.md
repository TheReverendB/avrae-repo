An alias for the Neclace of Prayer Beads.

**April 2024 Update:**  Should support changes for the 2024 version of this item.
 
`!nPrayerBeads roll new`
Rolls randomly for the beads on your necklace.
 
`!nPrayerBeads cast <spell> [casting arguments]`
This will cast the coresponding spell and consume a bead.
```
Bead of...   | Spell
-------------|--------------------
Blessing     | Bless
Curing       | Cure Wounds
             |  (2nd level) or
             |  Lesser Restoration
Favor        | Greater Restoration
Smiting      | Branding Smite or 
             |  (2024) Shining Smite 
Summons      | Planar Ally or 
             |  (2024) Guardian of Faith
Wind Walking | Wind Walk
```
 
Specify the spell:
 
`!nPrayerBeads cast "cure wounds"` or
`!nPrayerBeads cast wind`
 
Partial matching will work. Use the typical casting arguments for this, just like `!cast`.
  
 
**Manually Setting the Beads**:
 
`!nPrayerBeads set [type] [type]...`
 
Enter up to six types, separated by spaces, to set the types of beads on the neclace.
Use the following options to set the beads:
 
`Blessing`, `Curing`, `Favor`, `Smiting`, `Summons`, `'Wind Walking'`
 
**Manual Reset**:
`!nPrayerBeads reset` will reset the use of all beads on your necklace.
 
 
The alias is currently set up with a counter to automatically reset the beads on the necklace after a long rest.  If you would like to only use the manual reset option, you can copy/paste the following: `!cc create "Necklace of Prayer Beads" -min 0 -max 1 -type bubble` and tell Avrae to overwrite the existing counter with the same name.
 
 
Support the work I do with [Ko-Fi](https://ko-fi.com/thereverendb)
 
The code behind these aliases will be posted as available on my  [Github](https://github.com/TheReverendB/avrae-aliases)