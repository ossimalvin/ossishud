# ossi's HUD
Some simple modifications to the default Team Fortress 2 user interface

## Contributing
Open up an issue before you open a pull request, as if you make a pull request I'm likely to shoot it down your work if I don't personally like it. Also try to take the time to read the guidelines.

## The basic guidelines of the project
* A more readable interface. This means modifying elements, such as the taunt menu, to be more compact and less intrusive. Also (Still to be done) a centred mode for the HUD that can be toggled using *cl_hud_minmode*.

* Customisation. Users should be able to perform basic modifications without having to learn VGUI, and should not have to go through a thousand lines of unreadable nonsense to perform more advanced modifications.

* Retain the style and soul of the default interface. This means there wont be any modifications to the default scheme (For the most part).

* Minimise file size. No files will be included that aren't needed. Bloated files, such as *ui/mainmenu.res* should be split apart to make the code more readable. This also improves customisation as it allows the user to easily disable/enable features that they don't/do want using the *#base* system.

## Todo list
* Remove top bar?
* Clean up spectator UI
* Target ID
