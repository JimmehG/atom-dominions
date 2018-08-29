# atom-dominions
Syntax highlighting for Dominions 5 data files in Atom.

## Dominions 5 mod data files.

This package contains a grammar file for syntax highlighting of Dominions 5 mod data files in the Atom editor. The language for Dominions 5 mod data files is an extremely simple declarative language where basically every command is a keyword. There is a form of scoping, and the arguments for the commands are weakly typed. These features, together with our efforts to catch as many mistakes as possible as early as possible, generated a large grammar file.

Anyway, this opens the door to edit Dominions 5 mod data files in Atom, with all the advantages that a modern text editor has: syntax highlighting, code folding (indentation based), text completion, etc.

From version 0.2 onwards there is also a snippets file. The snippets available are for commands like #selectspell and #newspell; a simple mnemonic is to write the command name without # and hit tab.

## Some Issues.

The syntax highlighting was tested not only on my mods, but also on the latest versions of Worthy Heroes and Red Rob's mods: Pretenders Enhanced, Magic Enhanced and Fantastic Mercs. All the provably false negatives expunged. I have tried to be as thorough as possible, but it is possible that some more obscure command is still lacking -- blame the manual.

## Future Plans.

There are still a couple of things that could be done to ease editing Dominions 5 files. One example is an easy and handy way of inserting all those magic values that **lots** of commands use, say by symbolic name instead of number.

Another goal, is to hook up the grammar to the linter so that you can jump to an error by clicking (or a keybindind). Need to learn the linter API first, though.
