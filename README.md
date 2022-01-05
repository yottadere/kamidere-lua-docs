# Overview

### Information

LUA engine: [**LuaJIT**](https://github.com/LuaJIT/LuaJIT) **v2.0.5**

Modules:

* [ffi](https://luajit.org/ext_ffi_api.html) - calling external C functions and using C data structures
* [bit](https://bitop.luajit.org/api.html) - bit operations
* [jit](https://luajit.org/ext_jit.html) - just-in-time lua compiler behavior control
* [coroutine](https://www.lua.org/manual/5.1/manual.html#5.2) - collaborative multithreading
* [string](https://www.lua.org/manual/5.1/manual.html#5.4) - strings manipulation
* [math](https://www.lua.org/manual/5.1/manual.html#5.6) - built-in mathematic functions

### Examples

* [movement-indicators](https://github.com/k1nd0f/movement-indicators) - k1nd0f
* [morgen-soundpack](https://github.com/yottadere/morgen-soundpack) - me

### Source interfaces and fields

* [Engine](doc/interfaces/engine.md)
* [EventListener](doc/interfaces/eventlistener.md)
* [CVar](doc/interfaces/cvar.md)
* [EntityList](doc/interfaces/entitylist.md)
* [GlobalVars](doc/interfaces/globalvars.md)
* [ClientState](doc/interfaces/clientstate.md)
* [Surface](doc/interfaces/surface.md)
* [Panorama](doc/interfaces/panorama.md)

### Hack tables and fields

* [Hooks](doc/hack/hooks.md)
* [Render](doc/hack/render.md)
* [Esp](doc/hack/esp.md)
* [Menu](doc/hack/menu.md)
* [Prediction](doc/hack/prediction.md)
* [Packet](doc/hack/packet.md)
* [Netvars](doc/hack/netvars.md)
* [Utils](doc/hack/utils.md)
* [Log](doc/hack/log.md)

### Data Types

* [Color](doc/datatypes/color.md)
* [Vector2D](doc/datatypes/vector2d.md)
* [Vector](doc/datatypes/vector.md)
* [QAngle](doc/datatypes/qangle.md)
* [EspBounds](doc/datatypes/espbounds.md)


### Classes

* [IGameEvent](doc/classes/igameevent.md)
* [INetChannelInfo](doc/classes/inetchannelinfo.md)
* [CBaseEntity](doc/classes/cbaseentity.md)
* [CBaseCombatWeapon](doc/classes/cbasecombatweapon.md)
* [CUserCmd](doc/classes/cusercmd.md)
* [CConVar](doc/classes/cconvar.md)
* [PlayerInfo](doc/classes/playerinfo.md)

### Enums

* [ECommandButtons](doc/enums/ecommandsbuttons.md) - flags, describe iButtons in CUserCmd
* [EFlags](doc/enums/eflags.md) - flags, describe entity state
* [EMoveType](doc/enums/emovetype.md) - values, describe entity movetype
* [EDrawPosition](doc/enums/edrawposition.md) - values, describe esp draw position
* [ERoundCorners](doc/enums/eroundcorners.md) - flags, describe corners round
* [EPolygonFlags](doc/enums/epolygonflags.md) - flags, describe polygon draw type
* [ECircleFlags](doc/enums/ecircleflags.md) - flags, describe circle draw type
* [ERectFlags](doc/enums/erectflags.md) - flags, describe rect draw type
* [ETextFlags](doc/enums/etextflags.md) - flags, describe text draw type
* [EFlow](doc/enums/eflow.md) - values, describe netchannel flow
* [ESliderFlags](doc/enums/esliderflags.md) - flags, describe slider settings
* [EColorEditFlags](doc/enums/ecoloreditflags.md) - flags, describe coloredit settings

