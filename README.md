# Sublime Text integration for cppfront

This is my implementation of syntax highlighting for Herb Sutter's [cppfront](https://github.com/hsutter/cppfront) project.

This implementation is intended for use in Sublime 4. Both cppfront and C++ code are supported.


### Installation:

1) Download the repo from [GitHub](https://github.com/12Thanjo/cppfront-sublime).
2) Open the Sublime packages folder
	- open Sublime Text
	- Preferences > Browse Packages
3) Create `User` directory if not already created
4) Insert the repo anywhere in this `User` directory, including sub-directories
5) A restart may be required, but otherwise you are good to go!


### Snippets:
Snippets are intended to be included at some point. I'm not sure when (I'm sadly quite slow at the moment), but hopefully soon.


### Support:
Have I missed something? Have I mislabelled something? Is there a bug?

Feel free to let me know. Pull Requests / fixes are appreciated, but definitely not required.

Thanks :)


##### Known bugs:
There are two bugs that I currently know of that I haven't found a fix for yet:

- Class constructor declarations sometimes are highlighted as function calls rather than declarations
- The `<>` with templates, when nested, get highlighted like they are operators. This happens with the built in C++ syntax highlighting as well, so there may not be a fix


