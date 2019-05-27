## v0.1.0
* Initial release

## v0.2.0
* Added two missing commands from Dominions 4, #exactgold and #transform.
* Added start and end folder markers.
* Added new Dominions v5.11 armor commands.
* Added snippets file.

## v0.3.0
* Massive grammar refactoring.
* Grammar structure cleaned.
* Scoping very much improved.
* Grammar completed (or nearly completed) with new Dominions 5 commands up until patch v5.24.
* Narrowed command arguments as much as possible.
* Several grammar fixes.
* Added language settings file.
* Readme improvements.
* Snippets improvements.

## v0.3.1
* Fix error in #scry.
* Clarify size issue in readme.
* Fix nations regexp.
* Fix montag regexps.
* Fix #flyspr, #hpoverslow, #poisonskin, #flightspr, #swift, #itemcost, #extramsg regexps.
* rewrite #reform rule.
* added montag arguments to various site recruit and summon commands.
* added montag arguments to various event recruit and summon commands.
* added missing #3com command.

## v0.3.2
* Added 0 as possible argument for #secondarylevel.
* Added -1 as possible argument for #len.
* Extended argument of #magicboost to -10.
* Added #clear command for weapons and armor.
* #incscale and #decscale also work for items.
* Added #[2-4]d3units event commands.
* #guardspirit takes montag values as argument.
* Added #limitedregen command.
* Fix #newitem regexp.
* Fix #newspell snippet.
* Add #newevent snippet.

## v0.3.3
* Fixed #mainlevel and #secondarylevel commands.
* Add new monster & item commands #ivylord, #dragonlord, #lamialord, #corpselord.
* Add new monster & item commands #alchemy, #warning, #deadhp.
* Add monster commands #indepspells, #corpseeater.
* Add item commands #hp, #recuperation, #yearaging, #noaging, #noagingland.
* Add item commands #noforgebonus, #stealthboost.
* Add word boundary to regexps for commands with enum args to tighten error recognition.

## v0.3.4
* Fix release v.0.3.3 (sigh).

## v0.3.5
* Add -1 to #restricted and #nationrebate command argument.
* Add negative arguments to #(path)blessbonus.
* Add undocumented #latehero command.
* Add negative arguments to #addupkeep.
* Add #carcasscollector command.
* Fixed wrong type of #(monster)lord command argument.
* Add undocumented #mountainlabcost and #mountaintemplecost commands.

## v0.3.6
* Fix changelog typos.
* Fix #itemcost regexp.
* Fix #hpoverslow and #poisonskin regexps.
* #stealthy can take no args.
* new weapon numbers start at 700 not 800.
* new armor numbers start at 250 not 300.
* Add blood sacrifice (33) to #req_targorder arguments.
* Allow #magicskill to take level 0 argument (to clear the magic level).
* #formationfighter accepts negative arguments.
* #speciallook also works for items.
* Added special orders to #req_targorder (but bitmasking not in yet).

## v0.3.7: to be released:
* #killcappop accepts negative arguments.
* Improve #idealcold regexp.
* #patience accepts negative arguments.
* Added #req_thronesite from v5.27 patch.
* #version and #domversion regexps accept optional patch number.
* v5.32: #newarmor and #newweapon accept optional arguments.
