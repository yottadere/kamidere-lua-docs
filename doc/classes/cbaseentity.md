# CBaseEntity

## Prop manipulations

Offsets can be obtained from [Netvars](../hack/netvars.md) table.

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
| Vector | GetAbsOrigin | () | - |
| QAngle | GetAbsAngles | () | - |
| void | SetAbsOrigin | (Vector vecNew) | - |
| void | SetAbsAngles | (QAngle angNew) | - |
| int | GetMoveType | () | - |
| float | GetNextAttack | () | - |
| void* | GetActiveWeaponHandle | () | - |
| string | GetClassname | () | - |
| bool | IsPlayer | () | - |
| Vector | GetEyePosition | () | - |
| void | UpdateCollisionBounds | () | - |
| [CBaseCombatWeapon](../classes/cbasecombatweapon.md)* | GetWeapon | () | - |
| bool | IsEnemy | (CBaseEntity* pEntity) | - |
| bool | IsVisible | (CBaseEntity* pEntity, Vector vecSpot, bool bSmokeCheck) | - |
| bool | CanShoot | ([CBaseCombatWeapon](../classes/cbasecombatweapon.md)* pWeapon) | - |
| Vector | GetBonePosition | (int iBone) | - |
| Vector | GetHitboxPosition | (int iHitbox) | - |
| Vector | GetHitGroupPosition | (int iHitGroup) | - |
| QAngle | GetViewPunch | () | - |
| QAngle | GetPunch | () | - |
| Vector | GetViewOffset | () | - |
| float | GetFriction | () | - |
| int | GetTickBase | () | - |
| Vector | GetVelocity | () | - |
| Vector | GetBaseVelocity | () | - |
| void* | GetGroundEntityHandle | () | - |
| int | GetHealth | () | - |
| int | GetLifeState | () | - |
| float | GetMaxSpeed | () | - |
| int | GetFlags | () | - |
| int | GetObserverMode | () | - |
| void* | GetObserverTargetHandle | () | - |
| void* | GetViewModelHandle | () | - |
| int | GetEFlags | () | - |
| float | GetSurfaceFriction | () | - |
| int | GetShotsFired | () | - |
| int | GetMoney | () | - |
| int | GetTotalHits | () | - |
| int | GetArmor | () | - |
| QAngle | GetEyeAngles | () | - |
| bool | IsDefusing | () | - |
| bool | IsScoped | () | - |
| bool | IsGrabbingHostage | () | - |
| bool | IsRescuing | () | - |
| bool | HasHelmet | () | - |
| bool | HasHeavyArmor | () | - |
| bool | HasDefuser | () | - |
| bool | HasImmunity | () | - |
| bool | IsInBuyZone | () | - |
| float | GetFlashAlpha | () | - |
| float | GetFlashDuration | () | - |
| int | GetGlowIndex | () | - |
| float | GetLowerBodyYaw | () | - |
| int | GetSurvivalTeam | () | - |
| int | IsUsedNewAnimState | () | - |
| float | GetAnimationTime | () | - |
| float | GetSimulationTime | () | - |
| float | GetOldSimulationTime | () | - |
| Vector | GetOrigin | () | - |
| QAngle | GetRotation | () | - |
| int | GetTeam | () | - |
| void* | GetOwnerEntityHandle | () | - |
| int | GetCollisionGroup | () | - |
| bool | IsSpotted | () | - |
