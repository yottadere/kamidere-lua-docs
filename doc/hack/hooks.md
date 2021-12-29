# Hooks

## Functions

| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| void | RegisterCallback | (string szEvent, function fnCallback) | register your callback to be called on a hack event |
| void | UnregisterCallback | (string szEvent) | unregister all your callbacks from this event |

## Events

| Name | Args | Description |
| :--- | :--- | :--- |
| OnDraw | - | - |
| OnCreateMove | ([CUserCmd](../classes/cusercmd.md)* pCmd) | - |
| OnPredictionEnd | ([CUserCmd](../classes/cusercmd.md)* pCmd) | - |
| OnCreateMoveEnd | ([CUserCmd](../classes/cusercmd.md)* pCmd) | - |
| OnPlayerEsp | ([CBaseEntity](../classes/cbaseentity.md)* pEntity, [EspBounds](../datatypes/espbounds.md)* pBounds) | - |
| OnPlayerEspEnd | ([CBaseEntity](../classes/cbaseentity.md)* pEntity, [EspBounds](../datatypes/espbounds.md)* pBounds) | - |
| OnBombEsp | ([CBaseEntity](../classes/cbaseentity.md)* pEntity, [EspBounds](../datatypes/espbounds.md)* pBounds) | - |
| OnBombEspEnd | ([CBaseEntity](../classes/cbaseentity.md)* pEntity, [EspBounds](../datatypes/espbounds.md)* pBounds) | - |
| OnWeaponEsp | ([CBaseEntity](../classes/cbaseentity.md)* pEntity, [EspBounds](../datatypes/espbounds.md)* pBounds) | - |
| OnWeaponEspEnd | ([CBaseEntity](../classes/cbaseentity.md)* pEntity, [EspBounds](../datatypes/espbounds.md)* pBounds) | - |
| OnGrenadeEsp | ([CBaseEntity](../classes/cbaseentity.md)* pEntity, [EspBounds](../datatypes/espbounds.md)* pBounds) | - |
| OnGrenadeEspEnd | ([CBaseEntity](../classes/cbaseentity.md)* pEntity, [EspBounds](../datatypes/espbounds.md)* pBounds) | - |
| OnGameEvent | ([IGameEvent](../classes/igameevent.md)* pEvent) | hack event listener |
| OnFireEvent | ([IGameEvent](../classes/igameevent.md)* pEvent) | default csgo event listener |
| OnOverrideView | - | - |
| OnDoPostScreenEffects | - | - |