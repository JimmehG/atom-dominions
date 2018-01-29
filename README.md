# atom-dominions
Syntax highlighting for Dominions 5 data files in Atom.

## Dominions 5 mod data files.

This package contains a grammar file for syntax highlighting of Dominions 5 mod data files in the Atom editor. The language for Dominions 5 mod data files is an extremely simple declarative language where basically every command is a keyword. There is a form of scoping, and the arguments for the commands are weakly typed. These features, together with our efforts to catch as many mistakes as possible as early as possible, generated a large grammar file -- about 116Kb **is** large.

Anyway, this opens the door to edit Dominions 5 mod data files in Atom, with all the advantages that a modern text editor has: syntax highlighting, code folding (indentation based), text completion, etc.

From version 0.2 onwards there is also a snippets file. The snippets available are for commands like #selectspell and #newspell; a simple mnemonic is to write the command name, without # and any vowels and hit tab.

## Some Issues.

The syntax highlighting was tested not only on my mods, but also on the latest versions of Worthy Heroes and Red Rob's Extra Pretenders, and all the provably false negatives expunged. Furthermore, most of the new mod commands for Dominions 5 are still not in.

## Future Plans.

There are still a couple of things that could be done to ease editing Dominions 5 files. One example is an easy and handy way of inserting all those magic values that **lots** of commands use, say by symbolic name instead of number. Maybe I will get around to doing that -- if I first set myself to learn CoffeeScript. Another goal, this one a relatively easy one, is to add editing for Dominions 5 map files. But admittedly, this is low priority, as editing map files in a text editor instead of the map editor is more of a pointless, masochistic exercise than something actually productive.
