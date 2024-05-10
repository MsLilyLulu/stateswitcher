# stateswitcher
A state switcher library for Love2D based on files (one file=one state).



****I AM NOT THE CREATOR OF THIS LIBRARY. I AM SIMPLY UPLOADING IT HERE FOR EASIER ACCESS.****
****THIS LIBRARY IS LICENSED UNDER THE CC-BY 4.0/Creative Commons Attribution International 4.0****

Created by Daniel Duris, 2014

[Link to the license here](https://creativecommons.org/licenses/by/4.0/)

[Original Download Link](https://ambience.sk/love2d-a-state-switcher-class-lua/)

---

Simple state switcher class for Love2D / Lua that uses one file per state.

***Code example:***
```
state=require("stateswitcher")
state.switch("credits") -- switching to credits.lua
```
***Code example with passing a value:***
```
state=require("stateswitcher")
state.switch("credits;2;hello") -- passing 2 as the first value, "hello" as the second value
```

***Other advantages:***
- edit your code & save to see changes immediately after state switch (without leaving your program)

- reuse the functions from the previous states (to keep same behaviour) or redeclare the functions (to change behaviour)

- automate debugging - create a sequence of state switching with variables passed
