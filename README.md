# DefInput
A module for handling input device bindings for Defold

This will allow you to enable your players to rebind their inputs, and give you flexability to change your default key bindings from one place.

## Installation
You can use DefInput in your own project by adding this project as a [Defold library dependency](http://www.defold.com/manuals/libraries/). Open your game.project file and in the dependencies field under project add:

	https://github.com/subsoap/definput/archive/master.zip
  
Once added, you must require the main Lua module via

```
local definput = require("definput.definput")
```

TODO instructions