This mod is a fork of [Sokomine's apartment mod][upstream] from the commit [`86b9888`](https://github.com/Sokomine/apartment/commit/86b9888c703fd2711dd86f75102753024ebfac2b). This fork redone the formspec of apartment controller and added configuration copiers. Apart from that, this fork removed the apartment spawner, which was seldom used and glitched.

## Features
This mod provides a "Apartment Configuration Panel", which allows apartment owners to set up a self-service rental system. Upon renting by another player, all the locked blocks inside the apartment will become the player's.

This mod also provides an "Apartment Configuration Copier", for copying apartment configurations (i.e. category, description, size) to another not configured panel. To copy, punch a configured panel with the copier; to paste, right-click a not configured panel. When being pasted, the description will be altered if the original description ends with a number.

## Note
This mod, for the servers only using the panel, is a drop-in replacement. However, for those using the apartment spawner, this mod is not compactible.

[upstream]: https://github.com/Sokomine/apartment/


