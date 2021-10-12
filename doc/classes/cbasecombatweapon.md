# CBaseCombatWeapon

## Prop manipulations

Offsets can be obtained from [Netvars](doc/hack/netvars.md) table.

| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| int | GetPropInt | (int iOffset) | - |
| Vector | GetPropVector | (int iOffset) | - |
| float | GetPropFloat | (int iOffset) | - |
| bool | GetPropBool | (int iOffset) | - |
| string | GetPropString | (int iOffset) | - |
| void | SetPropInt | (int iOffset, int iNew) | - |
| void | SetPropVector | (int iOffset, Vector vecNew) | - |
| void | SetPropFloat | (int iOffset, float flNew) | - |
| void | SetPropBool | (int iOffset, bool bNew) | - |

## Functions

| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| bool | IsDormant | () | - |
| int | GetClassId | () | - |
| Vector | GetMins | () | - |
| Vector | GetMaxs | () | - |
| float | GetNextPrimaryAttack | () | - |
| float | GetNextSecondaryAttack | () | - |
| bool | IsWeapon | () | - |
| float | GetSpread | () | - |
| float | GetInaccuracy | () | - |
| void | UpdateAccuracyPenalty | () | - |
| int | GetAmmo | () | - |
| int | GetAmmoReserve | () | - |
| int | GetViewModelIndex | () | - |
| int | GetWorldModelIndex | () | - |
| void* | GetWorldModelHandle | () | - |
| bool | IsReloading | () | - |
| int | GetItemDefinitionIndex | () | - |
| int | GetItemIDHigh | () | - |
| int | GetItemIDLow | () | - |
| int | GetAccountID | () | - |
| int | GetEntityQuality | () | - |
| bool | IsInitialized | () | - |
| string | GetCustomName | () | - |
| int | GetOwnerXuidLow | () | - |
| int | GetOwnerXuidHigh | () | - |
| int | GetFallbackPaintKit | () | - |
| int | GetFallbackSeed | () | - |
| float | GetFallbackWear | () | - |
| int | GetFallbackStatTrak | () | - |