# Netvars

## Functions

| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| int | GetOffset | (string szPropName) | propname format: CBasePlayer->m_vecVelocity[0] |

```lua
local velOffset = Netvars.GetOffset("CBasePlayer->m_vecVelocity[0]")

local playerIndex = Engine.GetLocalPlayer()

local player = EntityList.GetEntityByIndex(playerIndex)

-- or player:GetVelocity()
local velocity = player:GetPropVector(velOffset)
```

## [CTestTraceline]    
int m_clrRender = 0x0070  
Vector m_vecOrigin = 0x0138  
float m_angRotation[0] = 0x012C  
float m_angRotation[1] = 0x0130  
float m_angRotation[2] = 0x0134  
int moveparent = 0x0148  
## [CTEWorldDecal]    
Vector m_vecOrigin = 0x0010  
int m_nIndex = 0x001C  
## [CTESpriteSpray]    
Vector m_vecOrigin = 0x0010  
Vector m_vecDirection = 0x001C  
int m_nModelIndex = 0x0028  
float m_fNoise = 0x0030  
int m_nCount = 0x0034  
int m_nSpeed = 0x002C  
## [CTESprite]    
Vector m_vecOrigin = 0x0010  
int m_nModelIndex = 0x001C  
float m_fScale = 0x0020  
int m_nBrightness = 0x0024  
## [CTESparks]    
int m_nMagnitude = 0x001C  
int m_nTrailLength = 0x0020  
Vector m_vecDir = 0x0024  
## [CTESmoke]    
Vector m_vecOrigin = 0x0010  
int m_nModelIndex = 0x001C  
float m_fScale = 0x0020  
int m_nFrameRate = 0x0024  
## [CTEShowLine]    
Vector m_vecEnd = 0x001C  
## [CTEProjectedDecal]    
Vector m_vecOrigin = 0x0010  
Vector m_angRotation = 0x001C  
float m_flDistance = 0x0028  
int m_nIndex = 0x002C  
## [CFEPlayerDecal]    
int m_nUniqueID = 0x09D8  
int m_unAccountID = 0x09DC  
int m_unTraceID = 0x09E0  
int m_rtGcTime = 0x09E4  
Vector m_vecEndPos = 0x09E8  
Vector m_vecStart = 0x09F4  
Vector m_vecRight = 0x0A00  
Vector m_vecNormal = 0x0A0C  
int m_nEntity = 0x0A1C  
int m_nPlayer = 0x0A18  
int m_nHitbox = 0x0A20  
int m_nTintID = 0x0A24  
float m_flCreationTime = 0x0A28  
byte m_nVersion = 0x0A2C  
void* m_ubSignature = 0x0A2D  
## [CTEPlayerDecal]    
Vector m_vecOrigin = 0x0014  
Vector m_vecStart = 0x0020  
Vector m_vecRight = 0x002C  
int m_nEntity = 0x0038  
int m_nPlayer = 0x0010  
int m_nHitbox = 0x003C  
## [CTEPhysicsProp]    
Vector m_vecOrigin = 0x0010  
float m_angRotation[0]     = 0x001C  
float m_angRotation[1]     = 0x0020  
float m_angRotation[2]     = 0x0024  
Vector m_vecVelocity = 0x0028  
int m_nModelIndex = 0x0034  
int m_nFlags = 0x003C  
int m_nSkin = 0x0038  
int m_nEffects = 0x0040  
int m_clrRender = 0x0044  
## [CTEParticleSystem]    
float m_vecOrigin[0]     = 0x0010  
float m_vecOrigin[1]     = 0x0014  
float m_vecOrigin[2]     = 0x0018  
## [CTEMuzzleFlash]    
Vector m_vecOrigin = 0x0010  
Vector m_vecAngles = 0x001C  
float m_flScale = 0x0028  
int m_nType = 0x002C  
## [CTELargeFunnel]    
int m_nModelIndex = 0x001C  
int m_nReversed = 0x0020  
## [CTEKillPlayerAttachments]    
int m_nPlayer = 0x0010  
## [CTEImpact]    
Vector m_vecOrigin = 0x0010  
Vector m_vecNormal = 0x001C  
int m_iType = 0x0028  
byte m_ucFlags = 0x002C  
## [CTEGlowSprite]    
Vector m_vecOrigin = 0x0010  
int m_nModelIndex = 0x001C  
float m_fScale = 0x0020  
float m_fLife = 0x0024  
int m_nBrightness = 0x0028  
## [CTEShatterSurface]    
Vector m_vecOrigin = 0x0010  
Vector m_vecAngles = 0x001C  
Vector m_vecForce = 0x0028  
Vector m_vecForcePos = 0x0034  
float m_flWidth = 0x0040  
float m_flHeight = 0x0044  
float m_flShardSize = 0x0048  
int m_nSurfaceType = 0x0050  
byte m_uchFrontColor[0]     = 0x0054  
byte m_uchFrontColor[1]     = 0x0055  
byte m_uchFrontColor[2]     = 0x0056  
byte m_uchBackColor[0]     = 0x0057  
byte m_uchBackColor[1]     = 0x0058  
byte m_uchBackColor[2]     = 0x0059  
## [CTEFootprintDecal]    
Vector m_vecOrigin = 0x0010  
Vector m_vecDirection = 0x001C  
int m_nEntity = 0x0034  
int m_nIndex = 0x0038  
byte m_chMaterialType = 0x003C  
## [CTEFizz]    
int m_nEntity = 0x0010  
int m_nModelIndex = 0x0014  
int m_nDensity = 0x0018  
int m_nCurrent = 0x001C  
## [CTEExplosion]    
int m_nModelIndex = 0x001C  
float m_fScale = 0x0020  
int m_nFrameRate = 0x0024  
int m_nFlags = 0x0028  
Vector m_vecNormal = 0x002C  
byte m_chMaterialType = 0x0038  
int m_nRadius = 0x003C  
int m_nMagnitude = 0x0040  
## [CTEEnergySplash]    
Vector m_vecPos = 0x0010  
Vector m_vecDir = 0x001C  
byte m_bExplosive = 0x0028  
## [CTEEffectDispatch]    
## [CEffectData]    
float m_vOrigin.x = 0x0010  
float m_vOrigin.y = 0x0014  
float m_vOrigin.z = 0x0018  
float m_vStart.x = 0x001C  
float m_vStart.y = 0x0020  
float m_vStart.z = 0x0024  
Vector m_vAngles = 0x0034  
Vector m_vNormal = 0x0028  
int m_fFlags = 0x0040  
float m_flMagnitude = 0x0050  
float m_flScale = 0x004C  
int m_nAttachmentIndex = 0x0058  
int m_nSurfaceProp = 0x005C  
int m_iEffectName = 0x0074  
int m_nMaterial = 0x0060  
int m_nDamageType = 0x0064  
int m_nHitBox = 0x0068  
int entindex = 0x0010  
int m_nOtherEntIndex = 0x006C  
byte m_nColor = 0x0070  
float m_flRadius = 0x0054  
byte m_bPositionsAreRelativeToEntity = 0x0071  
void* m_EffectData = 0x0010  
## [CTEDynamicLight]    
Vector m_vecOrigin = 0x0010  
int r = 0x0020  
int g = 0x0024  
int b = 0x0028  
int exponent = 0x002C  
float m_fRadius = 0x001C  
float m_fTime = 0x0030  
float m_fDecay = 0x0034  
## [CTEDecal]    
Vector m_vecOrigin = 0x0010  
Vector m_vecStart = 0x001C  
int m_nEntity = 0x0028  
int m_nHitbox = 0x002C  
int m_nIndex = 0x0030  
## [CTEClientProjectile]    
Vector m_vecOrigin = 0x0010  
Vector m_vecVelocity = 0x001C  
int m_nModelIndex = 0x0028  
int m_nLifeTime = 0x002C  
int m_hOwner = 0x0030  
## [CTEBubbleTrail]    
Vector m_vecMins = 0x0010  
Vector m_vecMaxs = 0x001C  
int m_nModelIndex = 0x002C  
float m_flWaterZ = 0x0028  
int m_nCount = 0x0030  
float m_fSpeed = 0x0034  
## [CTEBubbles]    
Vector m_vecMins = 0x0010  
Vector m_vecMaxs = 0x001C  
int m_nModelIndex = 0x002C  
float m_fHeight = 0x0028  
int m_nCount = 0x0030  
float m_fSpeed = 0x0034  
## [CTEBSPDecal]    
Vector m_vecOrigin = 0x0010  
int m_nEntity = 0x001C  
int m_nIndex = 0x0020  
## [CTEBreakModel]    
Vector m_vecOrigin = 0x0010  
float m_angRotation[0]     = 0x001C  
float m_angRotation[1]     = 0x0020  
float m_angRotation[2]     = 0x0024  
Vector m_vecSize = 0x0028  
Vector m_vecVelocity = 0x0034  
int m_nModelIndex = 0x0044  
int m_nRandomization = 0x0040  
int m_nCount = 0x0048  
float m_fTime = 0x004C  
int m_nFlags = 0x0050  
## [CTEBloodStream]    
Vector m_vecDirection = 0x001C  
int r = 0x0028  
int g = 0x002C  
int b = 0x0030  
int a = 0x0034  
int m_nAmount = 0x0038  
## [CTEBloodSprite]    
Vector m_vecOrigin = 0x0010  
Vector m_vecDirection = 0x001C  
int r = 0x0028  
int g = 0x002C  
int b = 0x0030  
int a = 0x0034  
int m_nSprayModel = 0x003C  
int m_nDropModel = 0x0038  
int m_nSize = 0x0040  
## [CTEBeamSpline]    
int m_nPoints = 0x00D0  
Vector m_vecPoints[0]     = 0x0010  
array[16]     m_vecPoints = 0x0000  
## [CTEBeamRingPoint]    
Vector m_vecCenter = 0x004C  
float m_flStartRadius = 0x0058  
float m_flEndRadius = 0x005C  
## [CTEBeamRing]    
int m_nStartEntity = 0x004C  
int m_nEndEntity = 0x0050  
## [CTEBeamPoints]    
Vector m_vecStartPoint = 0x004C  
Vector m_vecEndPoint = 0x0058  
## [CTEBeamLaser]    
int m_nStartEntity = 0x004C  
int m_nEndEntity = 0x0050  
## [CTEBeamFollow]    
int m_iEntIndex = 0x004C  
## [CTEBeamEnts]    
int m_nStartEntity = 0x004C  
int m_nEndEntity = 0x0050  
## [CTEBeamEntPoint]    
int m_nStartEntity = 0x004C  
int m_nEndEntity = 0x0050  
Vector m_vecStartPoint = 0x0054  
Vector m_vecEndPoint = 0x0060  
## [CBaseBeam]    
int m_nModelIndex = 0x0010  
int m_nHaloIndex = 0x0014  
int m_nStartFrame = 0x0018  
int m_nFrameRate = 0x001C  
float m_fLife = 0x0020  
float m_fWidth = 0x0024  
float m_fEndWidth = 0x0028  
int m_nFadeLength = 0x002C  
float m_fAmplitude = 0x0030  
int m_nSpeed = 0x0044  
int r = 0x0034  
int g = 0x0038  
int b = 0x003C  
int a = 0x0040  
int m_nFlags = 0x0048  
## [CTEArmorRicochet]    
## [CTEMetalSparks]    
Vector m_vecPos = 0x0010  
Vector m_vecDir = 0x001C  
## [CSteamJet]    
float m_SpreadSpeed = 0x0AC4  
float m_Speed = 0x0AC8  
float m_StartSize = 0x0ACC  
float m_EndSize = 0x0AD0  
float m_Rate = 0x0AD4  
float m_JetLength = 0x0AD8  
int m_bEmit = 0x0ADC  
byte m_bFaceLeft = 0x0AE4  
int m_nType = 0x0AE0  
int m_spawnflags = 0x0AE8  
float m_flRollSpeed = 0x0AEC  
## [CSmokeStack]    
float m_SpreadSpeed = 0x0B14  
float m_Speed = 0x0B18  
float m_StartSize = 0x0B1C  
float m_EndSize = 0x0B20  
float m_Rate = 0x0B24  
float m_JetLength = 0x0B28  
int m_bEmit = 0x0B2C  
float m_flBaseSpread = 0x0B30  
float m_flTwist = 0x0B84  
float m_flRollSpeed = 0x0BC0  
int m_iMaterialModel = 0x0B88  
Vector m_AmbientLight.m_vPos = 0x0B34  
Vector m_AmbientLight.m_vColor = 0x0B40  
float m_AmbientLight.m_flIntensity = 0x0B4C  
Vector m_DirLight.m_vPos = 0x0B50  
Vector m_DirLight.m_vColor = 0x0B5C  
float m_DirLight.m_flIntensity = 0x0B68  
Vector m_vWind = 0x0B78  
## [CDustTrail]    
float m_SpawnRate = 0x0AC4  
Vector m_Color = 0x0AC8  
float m_ParticleLifetime = 0x0AD8  
float m_StopEmitTime = 0x0AE0  
float m_MinSpeed = 0x0AE4  
float m_MaxSpeed = 0x0AE8  
float m_MinDirectedSpeed = 0x0AEC  
float m_MaxDirectedSpeed = 0x0AF0  
float m_StartSize = 0x0AF4  
float m_EndSize = 0x0AF8  
float m_SpawnRadius = 0x0AFC  
byte m_bEmit = 0x0B0C  
float m_Opacity = 0x0AD4  
## [CFireTrail]    
int m_nAttachment = 0x0AC4  
float m_flLifetime = 0x0AC8  
## [CSporeTrail]    
float m_flSpawnRate = 0x0ACC  
Vector m_vecEndColor = 0x0AC0  
float m_flParticleLifetime = 0x0AD0  
float m_flStartSize = 0x0AD4  
float m_flEndSize = 0x0AD8  
float m_flSpawnRadius = 0x0ADC  
byte m_bEmit = 0x0AEC  
## [CSporeExplosion]    
float m_flSpawnRate = 0x0AC4  
float m_flParticleLifetime = 0x0AC8  
float m_flStartSize = 0x0ACC  
float m_flEndSize = 0x0AD0  
float m_flSpawnRadius = 0x0AD4  
byte m_bEmit = 0x0ADC  
byte m_bDontRemove = 0x0ADD  
## [CRocketTrail]    
float m_SpawnRate = 0x0AC4  
Vector m_StartColor = 0x0AC8  
Vector m_EndColor = 0x0AD4  
float m_ParticleLifetime = 0x0AE4  
float m_StopEmitTime = 0x0AE8  
float m_MinSpeed = 0x0AEC  
float m_MaxSpeed = 0x0AF0  
float m_StartSize = 0x0AF4  
float m_EndSize = 0x0AF8  
float m_SpawnRadius = 0x0AFC  
byte m_bEmit = 0x0B0C  
int m_nAttachment = 0x0B10  
float m_Opacity = 0x0AE0  
byte m_bDamaged = 0x0B0D  
float m_flFlareScale = 0x0B20  
## [CSmokeTrail]    
float m_SpawnRate = 0x0AC4  
Vector m_StartColor = 0x0AC8  
Vector m_EndColor = 0x0AD4  
float m_ParticleLifetime = 0x0AE4  
float m_StopEmitTime = 0x0AE8  
float m_MinSpeed = 0x0AEC  
float m_MaxSpeed = 0x0AF0  
float m_MinDirectedSpeed = 0x0AF4  
float m_MaxDirectedSpeed = 0x0AF8  
float m_StartSize = 0x0AFC  
float m_EndSize = 0x0B00  
float m_SpawnRadius = 0x0B04  
byte m_bEmit = 0x0B14  
int m_nAttachment = 0x0B18  
float m_Opacity = 0x0AE0  
## [CPropVehicleDriveable]    
int m_hPlayer = 0x2994  
int m_nSpeed = 0x2998  
int m_nRPM = 0x299C  
float m_flThrottle = 0x29A0  
int m_nBoostTimeLeft = 0x29A4  
int m_nHasBoost = 0x29A8  
int m_nScannerDisabledWeapons = 0x29AC  
int m_nScannerDisabledVehicle = 0x29B0  
byte m_bEnterAnimOn = 0x29D0  
byte m_bExitAnimOn = 0x29D1  
byte m_bUnableToFire = 0x2A1D  
Vector m_vecEyeExitEndpoint = 0x2A10  
byte m_bHasGun = 0x2A1C  
Vector m_vecGunCrosshair = 0x29D8  
## [CParticleSmokeGrenade]    
float m_flSpawnTime = 0x0AD4  
float m_FadeStartTime = 0x0AD8  
float m_FadeEndTime = 0x0ADC  
Vector m_MinColor = 0x0AE4  
Vector m_MaxColor = 0x0AF0  
int m_CurrentStage = 0x0AC4  
## [CParticleFire]    
Vector m_vOrigin = 0x0ACC  
Vector m_vDirection = 0x0AD8  
## [CMovieExplosion]    
## [CTEGaussExplosion]    
int m_nType = 0x001C  
Vector m_vecDirection = 0x0020  
## [CQuadraticBeam]    
Vector m_targetPosition = 0x09D8  
Vector m_controlPosition = 0x09E4  
float m_scrollRate = 0x09F0  
float m_flWidth = 0x09F4  
## [CEmbers]    
int m_nDensity = 0x09D8  
int m_nLifetime = 0x09DC  
int m_nSpeed = 0x09E0  
byte m_bEmit = 0x09E4  
## [CEnvWind]    
## [CEnvWindShared]    
int m_iMinWind = 0x09E4  
int m_iMaxWind = 0x09E8  
int m_iMinGust = 0x09F0  
int m_iMaxGust = 0x09F4  
float m_flMinGustDelay = 0x09F8  
float m_flMaxGustDelay = 0x09FC  
int m_iGustDirChange = 0x0A04  
int m_iWindSeed = 0x09E0  
int m_iInitialWindDir = 0x0A44  
float m_flInitialWindSpeed = 0x0A48  
float m_flStartTime = 0x09DC  
float m_flGustDuration = 0x0A00  
void* m_EnvWindShared = 0x09D8  
## [CPrecipitation]    
int m_nPrecipType = 0x0A00  
## [CPrecipitationBlocker]    
## [CBaseTempEntity]    
## [CNextBot]    
## [CWearableItem]    
## [CBaseAttributableItem]    
## [CAttributeContainer]    
int m_hOuter = 0x2DAC  
int m_ProviderType = 0x2DB4  
int m_iReapplyProvisionParity = 0x2DA8  
## [CScriptCreatedItem]    
short m_iItemDefinitionIndex = 0x2FBA  
int m_iEntityLevel = 0x2FC0  
int m_iItemIDHigh = 0x2FD0  
int m_iItemIDLow = 0x2FD4  
int m_iAccountID = 0x2FD8  
int m_iEntityQuality = 0x2FBC  
byte m_bInitialized = 0x2FE4  
char[161]     m_szCustomName = 0x304C  
## [CAttributeList]    
void* m_Attributes = 0x3030  
void* m_NetworkedDynamicAttributesForDemos = 0x3030  
void* m_Item = 0x2DD0  
void* m_AttributeManager = 0x2D90  
int m_OriginalOwnerXuidLow = 0x31D0  
int m_OriginalOwnerXuidHigh = 0x31D4  
int m_nFallbackPaintKit = 0x31D8  
int m_nFallbackSeed = 0x31DC  
float m_flFallbackWear = 0x31E0  
int m_nFallbackStatTrak = 0x31E4  
## [CEconEntity]    
## [CAttributeContainer]    
int m_hOuter = 0x2DAC  
int m_ProviderType = 0x2DB4  
int m_iReapplyProvisionParity = 0x2DA8  
## [CScriptCreatedItem]    
short m_iItemDefinitionIndex = 0x2FBA  
int m_iEntityLevel = 0x2FC0  
int m_iItemIDHigh = 0x2FD0  
int m_iItemIDLow = 0x2FD4  
int m_iAccountID = 0x2FD8  
int m_iEntityQuality = 0x2FBC  
byte m_bInitialized = 0x2FE4  
char[161]     m_szCustomName = 0x304C  
## [CAttributeList]    
void* m_Attributes = 0x3030  
void* m_NetworkedDynamicAttributesForDemos = 0x3030  
void* m_Item = 0x2DD0  
void* m_AttributeManager = 0x2D90  
int m_OriginalOwnerXuidLow = 0x31D0  
int m_OriginalOwnerXuidHigh = 0x31D4  
int m_nFallbackPaintKit = 0x31D8  
int m_nFallbackSeed = 0x31DC  
float m_flFallbackWear = 0x31E0  
int m_nFallbackStatTrak = 0x31E4  
## [CWeaponZoneRepulsor]    
## [CWeaponXM1014]    
int m_reloadState = 0x33E4  
## [CWeaponTaser]    
float m_fFireTime = 0x3400  
## [CWeaponTablet]    
float m_flUpgradeExpirationTime[0]     = 0x33E8  
array[4]     m_flUpgradeExpirationTime = 0x0000  
int m_vecLocalHexFlags[0]     = 0x33F8  
array[42]     m_vecLocalHexFlags = 0x0000  
int m_nContractKillGridIndex = 0x34A0  
int m_nContractKillGridHighResIndex = 0x34A4  
byte m_bTabletReceptionIsBlocked = 0x34A8  
float m_flScanProgress = 0x34AC  
float m_flBootTime = 0x34B0  
float m_flShowMapTime = 0x34B4  
int m_vecNotificationIds[0]     = 0x34C4  
array[8]     m_vecNotificationIds = 0x0000  
float m_vecNotificationTimestamps[0]     = 0x34E4  
array[8]     m_vecNotificationTimestamps = 0x0000  
Vector m_vecPlayerPositionHistory[0]     = 0x3508  
array[24]     m_vecPlayerPositionHistory = 0x0000  
int m_nLastPurchaseIndex = 0x3504  
Vector m_vecNearestMetalCratePos = 0x34B8  
## [CSnowball]    
## [CSmokeGrenade]    
## [CWeaponShield]    
float m_flDisplayHealth = 0x3400  
## [CWeaponSG552]    
## [CSensorGrenade]    
## [CWeaponSawedoff]    
int m_reloadState = 0x33E4  
## [CWeaponNOVA]    
int m_reloadState = 0x33E4  
## [CIncendiaryGrenade]    
## [CMolotovGrenade]    
## [CWeaponMelee]    
float m_flThrowAt = 0x33E0  
## [CWeaponM3]    
int m_reloadState = 0x33E4  
## [CWeaponKnifeGG]    
## [CWeaponKnife]    
## [CHEGrenade]    
## [CFlashbang]    
## [CWeaponFists]    
byte m_bPlayingUninterruptableAct = 0x33E0  
## [CWeaponElite]    
## [CDecoyGrenade]    
## [CWeaponDEagle]    
## [CWeaponUSP]    
## [CWeaponM249]    
## [CWeaponUMP45]    
## [CWeaponTMP]    
## [CWeaponTec9]    
## [CWeaponSSG08]    
## [CWeaponSG556]    
## [CWeaponSG550]    
## [CWeaponScout]    
## [CWeaponSCAR20]    
## [CWeaponSCAR17]    
## [CWeaponP90]    
## [CWeaponP250]    
## [CWeaponP228]    
## [CWeaponNegev]    
## [CWeaponMP9]    
## [CWeaponMP7]    
## [CWeaponMP5Navy]    
## [CWeaponMag7]    
## [CWeaponMAC10]    
## [CWeaponM4A1]    
## [CWeaponHKP2000]    
## [CWeaponGlock]    
## [CWeaponGalilAR]    
## [CWeaponGalil]    
## [CWeaponG3SG1]    
## [CWeaponFiveSeven]    
## [CWeaponFamas]    
## [CWeaponBizon]    
## [CWeaponAWP]    
## [CWeaponAug]    
## [CWeaponAK47]    
## [CWeaponCSBaseGun]    
int m_zoomLevel = 0x33E0  
int m_iBurstShotsRemaining = 0x33E4  
## [CWeaponCSBase]    
int m_weaponMode = 0x3328  
float m_fAccuracyPenalty = 0x3340  
float m_fLastShotTime = 0x33B8  
int m_iRecoilIndex = 0x3350  
float m_flRecoilIndex = 0x3354  
int m_hPrevOwner = 0x3394  
byte m_bBurstMode = 0x3358  
float m_flPostponeFireReadyTime = 0x335C  
byte m_bReloadVisuallyComplete = 0x3360  
byte m_bSilencerOn = 0x3361  
float m_flDoneSwitchingSilencer = 0x3364  
int m_iOriginalTeamNumber = 0x336C  
int m_iIronSightMode = 0x33D4  
## [CWeaponC4]    
byte m_bStartedArming = 0x3400  
byte m_bBombPlacedAnimation = 0x3408  
float m_fArmedTime = 0x3404  
byte m_bShowC4LED = 0x3409  
byte m_bIsPlantingViaUse = 0x340A  
## [CWeaponBumpMine]    
## [CBumpMineProjectile]    
int m_nParentBoneIndex = 0x29E4  
Vector m_vecParentBonePos = 0x29E8  
byte m_bArmed = 0x29F4  
## [CWeaponBreachCharge]    
## [CBreachChargeProjectile]    
byte m_bShouldExplode = 0x29E0  
int m_weaponThatThrewMe = 0x29E4  
int m_nParentBoneIndex = 0x29E8  
Vector m_vecParentBonePos = 0x29EC  
## [CWeaponBaseItem]    
byte m_bRedraw = 0x33EC  
## [CBaseCSGrenade]    
byte m_bRedraw = 0x33E0  
byte m_bIsHeldByPlayer = 0x33E1  
byte m_bPinPulled = 0x33E2  
float m_fThrowTime = 0x33E4  
byte m_bLoopingSoundPlaying = 0x33E8  
float m_flThrowStrength = 0x33EC  
float m_fDropTime = 0x33F0  
## [CSnowballProjectile]    
## [CSnowballPile]    
## [CSmokeGrenadeProjectile]    
byte m_bDidSmokeEffect = 0x2A24  
int m_nSmokeEffectTickBegin = 0x2A20  
## [CSensorGrenadeProjectile]    
## [CMolotovProjectile]    
byte m_bIsIncGrenade = 0x2A20  
## [CItem_Healthshot]    
## [CItemDogtags]    
int m_OwningPlayer = 0x3450  
int m_KillingPlayer = 0x3454  
## [CDecoyProjectile]    
## [CPhysPropRadarJammer]    
## [CPhysPropWeaponUpgrade]    
## [CPhysPropAmmoBox]    
## [CPhysPropLootCrate]    
byte m_bRenderInPSPM = 0x2A04  
byte m_bRenderInTablet = 0x2A05  
int m_iHealth = 0x0100  
int m_iMaxHealth = 0x2A08  
## [CItemCash]    
## [CEnvGasCanister]    
float m_flFlightSpeed = 0x2A04  
float m_flLaunchTime = 0x2A08  
Vector m_vecParabolaDirection = 0x2A1C  
float m_flFlightTime = 0x2A00  
float m_flWorldEnterTime = 0x2A28  
float m_flInitialZSpeed = 0x2A0C  
float m_flZAcceleration = 0x2A10  
float m_flHorizSpeed = 0x2A14  
byte m_bLaunchedFromWithinWorld = 0x2A18  
Vector m_vecImpactPosition = 0x29C4  
Vector m_vecStartPosition = 0x29D0  
Vector m_vecEnterWorldPosition = 0x29DC  
Vector m_vecDirection = 0x29E8  
Vector m_vecStartAngles = 0x29F4  
Vector m_vecSkyboxOrigin = 0x2A2C  
float m_flSkyboxScale = 0x2A38  
byte m_bInSkybox = 0x2A3C  
byte m_bDoImpactEffects = 0x2A3D  
byte m_bLanded = 0x2990  
int m_hSkyboxCopy = 0x29B8  
int m_nMyZoneIndex = 0x2A40  
Vector2D m_vecOrigin = 0x0138  
float m_vecOrigin[2]     = 0x0140  
## [CDronegun]    
Vector m_vecAttentionTarget = 0x2990  
Vector m_vecTargetOffset = 0x299C  
int m_iHealth = 0x0100  
byte m_bHasTarget = 0x29A8  
## [CParadropChopper]    
Vector2D m_vecOrigin = 0x0138  
float m_vecOrigin[2]     = 0x0140  
int m_hCallingPlayer = 0x29A0  
## [CSurvivalSpawnChopper]    
Vector2D m_vecOrigin = 0x0138  
float m_vecOrigin[2]     = 0x0140  
## [CBRC4Target]    
byte m_bBrokenOpen = 0x2994  
float m_flRadius = 0x2998  
## [CInfoMapRegion]    
float m_flRadius = 0x09D8  
char[128]     m_szLocToken = 0x09DC  
## [CFireCrackerBlast]    
## [CInferno]    
void* m_fireXDelta = 0x09E4  
void* m_fireYDelta = 0x0B74  
void* m_fireZDelta = 0x0D04  
void* m_bFireIsBurning = 0x0E94  
int m_nFireEffectTickBegin = 0x13B4  
int m_fireCount = 0x13A8  
## [CCChicken]    
int m_jumpedThisFrame = 0x29F8  
int m_leader = 0x29FC  
## [CDrone]    
int m_hMoveToThisEntity = 0x29E8  
int m_hDeliveryCargo = 0x29EC  
byte m_bPilotTakeoverAllowed = 0x29F0  
int m_hPotentialCargo = 0x29F4  
int m_hCurrentPilot = 0x29F8  
Vector m_vecTagPositions[0]     = 0x29FC  
array[24]     m_vecTagPositions = 0x0000  
int m_vecTagIncrements[0]     = 0x2B1C  
array[24]     m_vecTagIncrements = 0x0000  
## [CFootstepControl]    
char[16]     m_source = 0x0A10  
char[16]     m_destination = 0x0A20  
## [CCSGameRulesProxy]    
## [CCSGameRules]    
byte m_bFreezePeriod = 0x0020  
byte m_bMatchWaitingForResume = 0x0041  
byte m_bWarmupPeriod = 0x0021  
float m_fWarmupPeriodEnd = 0x0024  
float m_fWarmupPeriodStart = 0x0028  
byte m_bTerroristTimeOutActive = 0x002C  
byte m_bCTTimeOutActive = 0x002D  
float m_flTerroristTimeOutRemaining = 0x0030  
float m_flCTTimeOutRemaining = 0x0034  
int m_nTerroristTimeOuts = 0x0038  
int m_nCTTimeOuts = 0x003C  
byte m_bTechnicalTimeOut = 0x0040  
int m_iRoundTime = 0x0044  
int m_gamePhase = 0x0060  
int m_totalRoundsPlayed = 0x0064  
int m_nOvertimePlaying = 0x0068  
float m_timeUntilNextPhaseStarts = 0x005C  
float m_flCMMItemDropRevealStartTime = 0x0878  
float m_flCMMItemDropRevealEndTime = 0x087C  
float m_fRoundStartTime = 0x004C  
byte m_bGameRestart = 0x0054  
float m_flRestartRoundTime = 0x0050  
float m_flGameStartTime = 0x0058  
int m_iHostagesRemaining = 0x006C  
byte m_bAnyHostageReached = 0x0070  
byte m_bMapHasBombTarget = 0x0071  
byte m_bMapHasRescueZone = 0x0072  
byte m_bMapHasBuyZone = 0x0073  
byte m_bIsQueuedMatchmaking = 0x0074  
int m_nQueuedMatchmakingMode = 0x0078  
byte m_bIsValveDS = 0x007C  
byte m_bIsQuestEligible = 0x0881  
byte m_bLogoMap = 0x007D  
byte m_bPlayAllStepSoundsOnServer = 0x007E  
int m_iNumGunGameProgressiveWeaponsCT = 0x0080  
int m_iNumGunGameProgressiveWeaponsT = 0x0084  
int m_iSpectatorSlotCount = 0x0088  
byte m_bBombDropped = 0x09A4  
byte m_bBombPlanted = 0x09A5  
int m_iRoundWinStatus = 0x09A8  
int m_eRoundWinReason = 0x09AC  
float m_flDMBonusStartTime = 0x0454  
float m_flDMBonusTimeLength = 0x0458  
short m_unDMBonusWeaponLoadoutSlot = 0x045C  
byte m_bDMBonusActive = 0x045E  
byte m_bTCantBuy = 0x09B0  
byte m_bCTCantBuy = 0x09B1  
float m_flGuardianBuyUntilTime = 0x09B4  
void* m_iMatchStats_RoundResults = 0x09B8  
void* m_iMatchStats_PlayersAlive_T = 0x0AA8  
void* m_iMatchStats_PlayersAlive_CT = 0x0A30  
void* m_GGProgressiveWeaponOrderCT = 0x008C  
void* m_GGProgressiveWeaponOrderT = 0x017C  
void* m_GGProgressiveWeaponKillUpgradeOrderCT = 0x026C  
void* m_GGProgressiveWeaponKillUpgradeOrderT = 0x035C  
int m_MatchDevice = 0x044C  
byte m_bHasMatchStarted = 0x0450  
void* m_TeamRespawnWaveTimes = 0x0B20  
void* m_flNextRespawnWave = 0x0BA0  
int m_nNextMapInMapgroup = 0x0460  
void* m_nEndMatchMapGroupVoteTypes = 0x0C28  
void* m_nEndMatchMapGroupVoteOptions = 0x0C50  
int m_nEndMatchMapVoteWinner = 0x0C78  
byte m_bIsDroppingItems = 0x0880  
int m_iActiveAssassinationTargetMissionID = 0x0C20  
float m_fMatchStartTime = 0x0048  
char[260]     m_szTournamentEventName = 0x0464  
char[260]     m_szTournamentEventStage = 0x0568  
char[260]     m_szTournamentPredictionsTxt = 0x0770  
int m_nTournamentPredictionsPct = 0x0874  
char[260]     m_szMatchStatTxt = 0x066C  
int m_nGuardianModeWaveNumber = 0x0884  
int m_nGuardianModeSpecialKillsRemaining = 0x0888  
int m_nGuardianModeSpecialWeaponNeeded = 0x088C  
int m_nHalloweenMaskListSeed = 0x09A0  
int m_numGlobalGiftsGiven = 0x0898  
int m_numGlobalGifters = 0x089C  
int m_numGlobalGiftsPeriodSeconds = 0x08A0  
void* m_arrFeaturedGiftersAccounts = 0x08A4  
void* m_arrFeaturedGiftersGifts = 0x08B4  
void* m_arrProhibitedItemIndices = 0x08C4  
int m_numBestOfMaps = 0x099C  
void* m_arrTournamentActiveCasterAccounts = 0x098C  
int m_iNumConsecutiveCTLoses = 0x0C7C  
int m_iNumConsecutiveTerroristLoses = 0x0C80  
## [CSurvivalGameRules]    
Vector m_vecPlayAreaMins = 0x0D00  
Vector m_vecPlayAreaMaxs = 0x0D0C  
void* m_iPlayerSpawnHexIndices = 0x0D18  
void* m_SpawnTileState = 0x0E18  
float m_flSpawnSelectionTimeStart = 0x0EF8  
float m_flSpawnSelectionTimeEnd = 0x0EFC  
float m_flSpawnSelectionTimeLoadout = 0x0F00  
int m_spawnStage = 0x0F04  
float m_flTabletHexOriginX = 0x0F08  
float m_flTabletHexOriginY = 0x0F0C  
float m_flTabletHexSize = 0x0F10  
void* m_roundData_playerXuids = 0x0F18  
void* m_roundData_playerPositions = 0x1120  
void* m_roundData_playerTeams = 0x1224  
void* m_SurvivalGameRuleDecisionTypes = 0x1328  
void* m_SurvivalGameRuleDecisionValues = 0x1368  
float m_flSurvivalStartTime = 0x13A8  
void* m_SurvivalRules = 0x0D00  
## [CRetakeGameRules]    
int m_nMatchSeed = 0x14B8  
byte m_bBlockersPresent = 0x14BC  
byte m_bRoundInProgress = 0x14BD  
int m_iFirstSecondHalfRound = 0x14C0  
int m_iBombSite = 0x14C4  
void* m_RetakeRules = 0x13C0  
void* cs_gamerules_data = 0x0000  
## [CWeaponCubemap]    
## [CWeaponCycler]    
## [CTEPlantBomb]    
Vector m_vecOrigin = 0x0014  
int m_iPlayer = 0x0010  
int m_option = 0x0020  
## [CTEFireBullets]    
Vector m_vecOrigin = 0x0018  
float m_vecAngles[0]     = 0x0024  
float m_vecAngles[1]     = 0x0028  
int m_iWeaponID = 0x0034  
int m_weapon = 0x0030  
int m_iMode = 0x0038  
int m_iSeed = 0x003C  
int m_iPlayer = 0x0010  
float m_fInaccuracy = 0x0040  
float m_fSpread = 0x0048  
short m_nItemDefIndex = 0x0014  
int m_iSoundType = 0x004C  
float m_flRecoilIndex = 0x0044  
## [CTERadioIcon]    
int m_iAttachToClient = 0x0010  
## [CPlantedC4]    
byte m_bBombTicking = 0x2990  
int m_nBombSite = 0x2994  
float m_flC4Blow = 0x29A0  
float m_flTimerLength = 0x29A4  
float m_flDefuseLength = 0x29B8  
float m_flDefuseCountDown = 0x29BC  
byte m_bBombDefused = 0x29C0  
int m_hBombDefuser = 0x29C4  
## [CCSTeam]    
## [CCSPlayerResource]    
int m_iPlayerC4 = 0x165C  
int m_iPlayerVIP = 0x1660  
void* m_bHostageAlive = 0x167C  
void* m_isHostageFollowingSomeone = 0x1688  
void* m_iHostageEntityIDs = 0x1694  
Vector m_bombsiteCenterA = 0x1664  
Vector m_bombsiteCenterB = 0x1670  
void* m_hostageRescueX = 0x16C4  
void* m_hostageRescueY = 0x16D4  
void* m_hostageRescueZ = 0x16E4  
void* m_iMVPs = 0x16F4  
void* m_iArmor = 0x187C  
void* m_bHasHelmet = 0x1839  
void* m_bHasDefuser = 0x17F8  
void* m_iScore = 0x1980  
void* m_iCompetitiveRanking = 0x1A84  
void* m_iCompetitiveWins = 0x1B88  
void* m_iCompetitiveRankType = 0x1C8C  
void* m_iCompTeammateColor = 0x1CD0  
void* m_iLifetimeStart = 0x1DD4  
void* m_iLifetimeEnd = 0x1ED8  
void* m_bControllingBot = 0x1FDC  
void* m_iControlledPlayer = 0x2020  
void* m_iControlledByPlayer = 0x2124  
void* m_iBotDifficulty = 0x42A8  
void* m_szClan = 0x43AC  
void* m_nCharacterDefIndex = 0x47BC  
void* m_iTotalCashSpent = 0x48C0  
void* m_iGunGameLevel = 0x49C4  
void* m_iCashSpentThisRound = 0x4AC8  
void* m_nEndMatchNextMapVotes = 0x6A88  
byte m_bEndMatchNextMapAllVoted = 0x6B8C  
void* m_nActiveCoinRank = 0x4BCC  
void* m_nMusicID = 0x4CD0  
void* m_nPersonaDataPublicLevel = 0x4DD4  
void* m_nPersonaDataPublicCommendsLeader = 0x4ED8  
void* m_nPersonaDataPublicCommendsTeacher = 0x4FDC  
void* m_nPersonaDataPublicCommendsFriendly = 0x50E0  
void* m_bHasCommunicationAbuseMute = 0x51E4  
void* m_szCrosshairCodes = 0x5225  
void* m_iMatchStats_Kills_Total = 0x5B08  
void* m_iMatchStats_5k_Total = 0x601C  
void* m_iMatchStats_4k_Total = 0x5F18  
void* m_iMatchStats_3k_Total = 0x5E14  
void* m_iMatchStats_Damage_Total = 0x6120  
void* m_iMatchStats_EquipmentValue_Total = 0x6224  
void* m_iMatchStats_KillReward_Total = 0x6328  
void* m_iMatchStats_LiveTime_Total = 0x642C  
void* m_iMatchStats_Deaths_Total = 0x5D10  
void* m_iMatchStats_Assists_Total = 0x5C0C  
void* m_iMatchStats_HeadShotKills_Total = 0x6530  
void* m_iMatchStats_Objective_Total = 0x6634  
void* m_iMatchStats_CashEarned_Total = 0x6738  
void* m_iMatchStats_UtilityDamage_Total = 0x683C  
void* m_iMatchStats_EnemiesFlashed_Total = 0x6940  
## [CCSPlayer]    
## [CCSLocalPlayerExclusive]    
Vector2D m_vecOrigin = 0x0138  
float m_vecOrigin[2]     = 0x0140  
float m_flStamina = 0x103D8  
int m_iDirection = 0x103DC  
int m_iShotsFired = 0x103E0  
int m_nNumFastDucks = 0x103E4  
byte m_bDuckOverride = 0x103E8  
float m_flVelocityModifier = 0x103EC  
void* m_bPlayerDominated = 0x114E8  
void* m_bPlayerDominatingMe = 0x11529  
void* m_iWeaponPurchasesThisRound = 0x1156C  
short m_unActiveQuestId = 0x11378  
int m_nQuestProgressReason = 0x1137C  
int m_iRetakesOffering = 0x11CF4  
int m_iRetakesOfferingCard = 0x11CF8  
byte m_bRetakesHasDefuseKit = 0x11CFC  
byte m_bRetakesMVPLastRound = 0x11CFD  
int m_iRetakesMVPBoostItem = 0x11D00  
int m_RetakesMVPBoostExtraUtility = 0x11D04  
int m_unPlayerTvControlFlags = 0x11380  
void* cslocaldata = 0x0000  
## [CCSNonLocalPlayerExclusive]    
void* csnonlocaldata = 0x0000  
## [CCSTeamExclusive]    
void* m_iWeaponPurchasesThisMatch = 0x10ACC  
void* m_EquippedLoadoutItemDefIndices = 0x112A4  
void* csteamdata = 0x0000  
float m_angEyeAngles[0]     = 0x113D0  
float m_angEyeAngles[1]     = 0x113D4  
int m_iAddonBits = 0x103C4  
int m_iPrimaryAddon = 0x103C8  
int m_iSecondaryAddon = 0x103CC  
int m_iThrowGrenadeCounter = 0x99B8  
byte m_bWaitForNoAttack = 0x99BC  
byte m_bIsRespawningForDMBonus = 0x99BD  
int m_iPlayerState = 0x9978  
int m_iAccount = 0x113B8  
int m_iStartAccount = 0x103F4  
int m_totalHitsOnServer = 0x103F8  
byte m_bInBombZone = 0x99B4  
byte m_bInBuyZone = 0x99B5  
byte m_bInNoDefuseArea = 0x99B6  
byte m_bKilledByTaser = 0x99CD  
int m_iMoveState = 0x99D0  
int m_iClass = 0x113C8  
int m_ArmorValue = 0x113CC  
Vector m_angEyeAngles = 0x113D0  
int m_bHasDefuser = 0x113DC  
int m_bNightVisionOn = 0x103E9  
byte m_bHasNightVision = 0x103EA  
byte m_bInHostageRescueZone = 0x113DD  
byte m_bIsDefusing = 0x997C  
byte m_bIsGrabbingHostage = 0x997D  
int m_iBlockingUseActionInProgress = 0x9980  
byte m_bIsScoped = 0x9974  
byte m_bIsWalking = 0x9975  
int m_nIsAutoMounting = 0x9AE4  
byte m_bResumeZoom = 0x9976  
float m_fImmuneToGunGameDamageTime = 0x9988  
byte m_bGunGameImmunity = 0x9990  
byte m_bHasMovedSinceSpawn = 0x9991  
byte m_bMadeFinalGunGameProgressiveKill = 0x9992  
int m_iGunGameProgressiveWeaponIndex = 0x9994  
int m_iNumGunGameTRKillPoints = 0x9998  
int m_iNumGunGameKillsWithCurrentWeapon = 0x999C  
int m_iNumRoundKills = 0x99A0  
float m_fMolotovUseTime = 0x99AC  
float m_fMolotovDamageTime = 0x99B0  
char[256]     m_szArmsModel = 0x99D7  
int m_hCarriedHostage = 0x10448  
int m_hCarriedHostageProp = 0x1044C  
byte m_bIsRescuing = 0x9984  
float m_flGroundAccelLinearFracLastTime = 0x103F0  
byte m_bCanMoveDuringFreezePeriod = 0x99D4  
byte m_isCurrentGunGameLeader = 0x99D5  
byte m_isCurrentGunGameTeamLeader = 0x99D6  
float m_flGuardianTooFarDistFrac = 0x99C0  
float m_flDetectedByEnemySensorTime = 0x99C4  
byte m_bIsPlayerGhost = 0x9AE1  
void* m_iMatchStats_Kills = 0x104B4  
void* m_iMatchStats_Damage = 0x1052C  
void* m_iMatchStats_EquipmentValue = 0x105A4  
void* m_iMatchStats_MoneySaved = 0x1061C  
void* m_iMatchStats_KillReward = 0x10694  
void* m_iMatchStats_LiveTime = 0x1070C  
void* m_iMatchStats_Deaths = 0x10784  
void* m_iMatchStats_Assists = 0x107FC  
void* m_iMatchStats_HeadShotKills = 0x10874  
void* m_iMatchStats_Objective = 0x108EC  
void* m_iMatchStats_CashEarned = 0x10964  
void* m_iMatchStats_UtilityDamage = 0x109DC  
void* m_iMatchStats_EnemiesFlashed = 0x10A54  
void* m_rank = 0x1138C  
void* m_passiveItems = 0x113A4  
byte m_bHasParachute = 0x113A4  
short m_unMusicID = 0x113A8  
byte m_bHasHelmet = 0x113C0  
byte m_bHasHeavyArmor = 0x113C1  
int m_nHeavyAssaultSuitCooldownRemaining = 0x113C4  
float m_flFlashDuration = 0x10470  
float m_flFlashMaxAlpha = 0x1046C  
int m_iProgressBarDuration = 0x103D0  
float m_flProgressBarStartTime = 0x103D4  
int m_hRagdoll = 0x1043C  
int m_hPlayerPing = 0x10440  
int m_cycleLatch = 0x114E0  
short m_unCurrentEquipmentValue = 0x11384  
short m_unRoundStartEquipmentValue = 0x11386  
short m_unFreezetimeEndEquipmentValue = 0x11388  
byte m_bIsControllingBot = 0x11A4D  
byte m_bHasControlledBotThisRound = 0x11A5C  
byte m_bCanControlObservedBot = 0x11A4E  
int m_iControlledBotEntIndex = 0x11A50  
Vector m_vecAutomoveTargetEnd = 0x9AF4  
float m_flAutoMoveStartTime = 0x9B04  
float m_flAutoMoveTargetTime = 0x9B08  
byte m_bIsAssassinationTarget = 0x11A4C  
byte m_bHud_MiniScoreHidden = 0x113FE  
byte m_bHud_RadarHidden = 0x113FF  
int m_nLastKillerIndex = 0x11400  
int m_nLastConcurrentKilled = 0x11404  
int m_nDeathCamMusic = 0x11408  
byte m_bIsHoldingLookAtWeapon = 0x11975  
byte m_bIsLookingAtWeapon = 0x11974  
int m_iNumRoundKillsHeadshots = 0x99A4  
int m_unTotalRoundDamageDealt = 0x99A8  
float m_flLowerBodyYawTarget = 0x9ADC  
byte m_bStrafing = 0x9AE0  
float m_flThirdpersonRecoil = 0x119EC  
byte m_bHideTargetID = 0x119F0  
byte m_bIsSpawnRappelling = 0x103FD  
Vector m_vecSpawnRappellingRopeOrigin = 0x10400  
int m_nSurvivalTeam = 0x10410  
int m_hSurvivalAssassinationTarget = 0x10414  
float m_flHealthShotBoostExpirationTime = 0x10418  
float m_flLastExoJumpTime = 0x9B0C  
void* m_vecPlayerPatchEconIndices = 0x119C4  
## [CPlayerPing]    
int m_hPlayer = 0x09E4  
int m_hPingedEntity = 0x09E8  
int m_iType = 0x09EC  
byte m_bUrgent = 0x09F4  
char[18]     m_szPlaceName = 0x09F5  
## [CCSRagdoll]    
Vector m_vecOrigin = 0x0138  
Vector m_vecRagdollOrigin = 0x2A1C  
int m_hPlayer = 0x2A00  
short m_nModelIndex = 0x0258  
int m_nForceBone = 0x268C  
Vector m_vecForce = 0x2680  
Vector m_vecRagdollVelocity = 0x2A10  
int m_iDeathPose = 0x2A28  
int m_iDeathFrame = 0x2A2C  
int m_iTeamNum = 0x00F4  
byte m_bClientSideAnimation = 0x28A0  
float m_flDeathYaw = 0x2A30  
float m_flAbsYaw = 0x2A34  
byte m_bDiedAirborne = 0x2A38  
## [CTEPlayerAnimEvent]    
int m_hPlayer = 0x0010  
int m_iEvent = 0x0014  
int m_nData = 0x0018  
## [CCHostage]    
int m_isRescued = 0x2F40  
int m_jumpedThisFrame = 0x2F41  
int m_iHealth = 0x0100  
int m_iMaxHealth = 0x2F28  
byte m_lifeState = 0x025F  
int m_fFlags = 0x0104  
int m_nHostageState = 0x2F44  
float m_flRescueStartTime = 0x2F48  
float m_flGrabSuccessTime = 0x2F4C  
float m_flDropStartTime = 0x2F50  
Vector m_vel = 0x2F34  
int m_leader = 0x2F30  
## [CHostageCarriableProp]    
## [CBaseCSGrenadeProjectile]    
Vector m_vInitialVelocity = 0x29E0  
int m_nBounces = 0x29EC  
int m_nExplodeEffectIndex = 0x29F0  
int m_nExplodeEffectTickBegin = 0x29F4  
Vector m_vecExplodeEffectOrigin = 0x29F8  
## [CHandleTest]    
int m_Handle = 0x09D8  
byte m_bSendHandle = 0x09DC  
## [CTeamplayRoundBasedRulesProxy]    
## [CTeamplayRoundBasedRules]    
int m_iRoundState = 0x0028  
byte m_bInWaitingForPlayers = 0x0038  
int m_iWinningTeam = 0x0030  
byte m_bInOvertime = 0x002C  
byte m_bInSetup = 0x002D  
byte m_bSwitchedTeamsThisRound = 0x002E  
byte m_bAwaitingReadyRestart = 0x0039  
float m_flRestartRoundTime = 0x003C  
float m_flMapResetTime = 0x0040  
void* m_flNextRespawnWave = 0x0044  
void* m_TeamRespawnWaveTimes = 0x00E8  
void* m_bTeamReady = 0x00C4  
byte m_bStopWatch = 0x00E4  
void* teamplayroundbased_gamerules_data = 0x0000  
## [CSpriteTrail]    
float m_flLifeTime = 0x1074  
float m_flStartWidth = 0x1078  
float m_flEndWidth = 0x107C  
float m_flStartWidthVariance = 0x1080  
float m_flTextureRes = 0x1084  
float m_flMinFadeLength = 0x1088  
Vector m_vecSkyboxOrigin = 0x108C  
float m_flSkyboxScale = 0x1098  
## [CSpriteOriented]    
## [CSprite]    
int m_hAttachedToEntity = 0x09E8  
int m_nAttachment = 0x09EC  
float m_flScaleTime = 0x0A08  
float m_flSpriteScale = 0x0A04  
float m_flSpriteFramerate = 0x09F0  
float m_flGlowProxySize = 0x0A10  
float m_flHDRColorScale = 0x0A14  
float m_flFrame = 0x09F4  
float m_flBrightnessTime = 0x0A00  
int m_nBrightness = 0x09FC  
byte m_bWorldSpaceScale = 0x0A0C  
## [CRagdoll_Attached]    
int m_boneIndexAttached = 0x2CC8  
int m_ragdollAttachedObjectIndex = 0x2CC4  
Vector m_attachmentPointBoneSpace = 0x2CA0  
Vector m_attachmentPointRagdollSpace = 0x2CB8  
## [CRagdoll]    
Vector m_ragAngles[0]     = 0x2AB0  
array[24]     m_ragAngles = 0x0000  
Vector m_ragPos[0]     = 0x2990  
array[24]     m_ragPos = 0x0000  
int m_hUnragdoll = 0x2C8C  
float m_flBlendWeight = 0x2C90  
int m_nOverlaySequence = 0x2C98  
## [CPropCounter]    
float m_flDisplayValue = 0x2990  
## [CPredictedViewModel]    
## [CPoseController]    
void* m_hProps = 0x09D8  
void* m_chPoseIndex = 0x09E8  
byte m_bPoseValueParity = 0x09EC  
float m_fPoseValue = 0x09F0  
float m_fInterpolationTime = 0x09F4  
byte m_bInterpolationWrap = 0x09F8  
float m_fCycleFrequency = 0x09FC  
int m_nFModType = 0x0A00  
float m_fFModTimeOffset = 0x0A04  
float m_fFModRate = 0x0A08  
float m_fFModAmplitude = 0x0A0C  
## [CGrassBurn]    
float m_flGrassBurnClearTime = 0x09D8  
## [CGameRulesProxy]    
## [CInfoLadderDismount]    
## [CFuncLadder]    
Vector m_vecPlayerMountPositionTop = 0x09F8  
Vector m_vecPlayerMountPositionBottom = 0x0A04  
Vector m_vecLadderDir = 0x09D8  
byte m_bFakeLadder = 0x0A11  
## [CTEFoundryHelpers]    
int m_iEntity = 0x0010  
## [CDetailController]    
float m_flFadeStartDist = 0x09D8  
float m_flFadeEndDist = 0x09DC  
## [CDangerZone]    
Vector m_vecDangerZoneOriginStartedAt = 0x09D8  
float m_flBombLaunchTime = 0x09E4  
float m_flExtraRadius = 0x09E8  
float m_flExtraRadiusStartTime = 0x09EC  
float m_flExtraRadiusTotalLerpTime = 0x09F0  
int m_nDropOrder = 0x09F4  
int m_iWave = 0x09F8  
## [CDangerZoneController]    
byte m_bDangerZoneControllerEnabled = 0x09D8  
byte m_bMissionControlledExplosions = 0x09D9  
float m_flStartTime = 0x09F4  
float m_flFinalExpansionTime = 0x09F8  
Vector m_vecEndGameCircleStart = 0x09DC  
Vector m_vecEndGameCircleEnd = 0x09E8  
void* m_DangerZones = 0x09FC  
void* m_flWaveEndTimes = 0x0AA4  
int m_hTheFinalZone = 0x0AB8  
## [CWorldVguiText]    
byte m_bEnabled = 0x09D8  
char[512]     m_szDisplayText = 0x09D9  
char[256]     m_szDisplayTextOption = 0x0BD9  
char[64]     m_szFont = 0x0CD9  
int m_iTextPanelWidth = 0x0D20  
int m_clrText = 0x0D19  
## [CWorld]    
float m_flWaveHeight = 0x09D8  
Vector m_WorldMins = 0x09DC  
Vector m_WorldMaxs = 0x09E8  
byte m_bStartDark = 0x09F4  
float m_flMaxOccludeeArea = 0x09F8  
float m_flMinOccluderArea = 0x09FC  
float m_flMaxPropScreenSpaceWidth = 0x0A04  
float m_flMinPropScreenSpaceWidth = 0x0A00  
char[256]     m_iszDetailSpriteMaterial = 0x0A10  
byte m_bColdWorld = 0x0A08  
int m_iTimeOfDay = 0x0A0C  
## [CWaterLODControl]    
float m_flCheapWaterStartDistance = 0x09D8  
float m_flCheapWaterEndDistance = 0x09DC  
## [CWaterBullet]    
## [CMapVetoPickController]    
int m_nDraftType = 0x09E8  
int m_nTeamWinningCoinToss = 0x09EC  
void* m_nTeamWithFirstChoice = 0x09F0  
void* m_nVoteMapIdsList = 0x0AF0  
void* m_nAccountIDs = 0x0B0C  
void* m_nMapId0 = 0x0C0C  
void* m_nMapId1 = 0x0D0C  
void* m_nMapId2 = 0x0E0C  
void* m_nMapId3 = 0x0F0C  
void* m_nMapId4 = 0x100C  
void* m_nMapId5 = 0x110C  
void* m_nStartingSide0 = 0x120C  
int m_nCurrentPhase = 0x130C  
int m_nPhaseStartTick = 0x1310  
int m_nPhaseDurationTicks = 0x1314  
## [CVoteController]    
int m_iActiveIssueIndex = 0x09E4  
int m_iOnlyTeamToVote = 0x09E8  
void* m_nVoteOptionCount = 0x09EC  
int m_nPotentialVotes = 0x0A04  
byte m_bIsYesNoVote = 0x0A0A  
## [CVGuiScreen]    
float m_flWidth = 0x09E0  
float m_flHeight = 0x09E4  
int m_fScreenFlags = 0x0A0C  
int m_nPanelName = 0x09E8  
int m_nAttachmentIndex = 0x0A04  
int m_nOverlayMaterial = 0x0A08  
int m_hPlayerOwner = 0x0A68  
## [CPropJeep]    
byte m_bHeadlightIsOn = 0x2ADC  
## [CPropVehicleChoreoGeneric]    
int m_hPlayer = 0x2A04  
byte m_bEnterAnimOn = 0x2A0C  
byte m_bExitAnimOn = 0x2A0D  
byte m_bForceEyesToAttachment = 0x2A1C  
Vector m_vecEyeExitEndpoint = 0x2A10  
byte m_vehicleView.bClampEyeAngles = 0x2AA0  
float m_vehicleView.flPitchCurveZero = 0x2AA4  
float m_vehicleView.flPitchCurveLinear = 0x2AA8  
float m_vehicleView.flRollCurveZero = 0x2AAC  
float m_vehicleView.flRollCurveLinear = 0x2AB0  
float m_vehicleView.flFOV = 0x2AB4  
float m_vehicleView.flYawMin = 0x2AB8  
float m_vehicleView.flYawMax = 0x2ABC  
float m_vehicleView.flPitchMin = 0x2AC0  
float m_vehicleView.flPitchMax = 0x2AC4  
## [CTriggerSoundOperator]    
int m_nSoundOperator = 0x0A10  
## [CBaseVPhysicsTrigger]    
## [CTriggerPlayerMovement]    
## [CBaseTrigger]    
byte m_bClientSidePredicted = 0x0A08  
int m_spawnflags = 0x02C8  
## [CProxyToggle]    
## [CProxyToggle_ProxiedData]    
int m_WithProxy = 0x09D8  
void* blah = 0x0000  
## [CTesla]    
char[64]     m_SoundName = 0x0A00  
char[256]     m_iszSpriteName = 0x0A40  
## [CBaseTeamObjectiveResource]    
int m_iTimerToShowInHUD = 0x09D8  
int m_iStopWatchTimer = 0x09DC  
int m_iNumControlPoints = 0x09E0  
byte m_bPlayingMiniRounds = 0x09E8  
byte m_bControlPointsReset = 0x09E9  
int m_iUpdateCapHudParity = 0x09EC  
Vector m_vCPPositions[0]     = 0x09F4  
array[8]     m_vCPPositions = 0x0000  
void* m_bCPIsVisible = 0x0A54  
void* m_flLazyCapPerc = 0x0A5C  
void* m_iTeamIcons = 0x0A9C  
void* m_iTeamOverlays = 0x0B9C  
void* m_iTeamReqCappers = 0x0C9C  
void* m_flTeamCapTime = 0x0D9C  
void* m_iPreviousPoints = 0x0E9C  
void* m_bTeamCanCap = 0x119C  
void* m_iTeamBaseIcons = 0x11DC  
void* m_iBaseControlPoints = 0x125C  
void* m_bInMiniRound = 0x12DC  
void* m_iWarnOnCap = 0x12E4  
char[255]     m_iszWarnSound[0]     = 0x1304  
array[8]     m_iszWarnSound = 0x0000  
void* m_flPathDistance = 0x1AFC  
void* m_iNumTeamMembers = 0x1B1C  
void* m_iCappingTeam = 0x1C1C  
void* m_iTeamInZone = 0x1C3C  
void* m_bBlocked = 0x1C5C  
void* m_iOwner = 0x1C64  
char[32]     m_pszCapLayoutInHUD = 0x1CEC  
## [CTeam]    
int m_iTeamNum = 0x0B68  
int m_bSurrendered = 0x0B6C  
int m_scoreTotal = 0x0B40  
int m_scoreFirstHalf = 0x0B44  
int m_scoreSecondHalf = 0x0B48  
int m_scoreOvertime = 0x0B4C  
int m_iClanID = 0x0B58  
char[32]     m_szTeamname = 0x09EC  
char[32]     m_szClanTeamname = 0x0A0C  
char[8]     m_szTeamFlagImage = 0x0A2C  
char[8]     m_szTeamLogoImage = 0x0A34  
char[260]     m_szTeamMatchStat = 0x0A3C  
int m_nGGLeaderEntIndex_CT = 0x0B50  
int m_nGGLeaderEntIndex_T = 0x0B54  
int m_numMapVictories = 0x0B70  
int player_array_element = 0x0000  
array[64]     "player_array" = 0x0000  
## [CSunlightShadowControl]    
Vector m_shadowDirection = 0x09D8  
byte m_bEnabled = 0x09E4  
char[260]     m_TextureName = 0x09E5  
int m_LightColor = 0x0AF0  
float m_flColorTransitionTime = 0x0B04  
float m_flSunDistance = 0x0B08  
float m_flFOV = 0x0B0C  
float m_flNearZ = 0x0B10  
float m_flNorthOffset = 0x0B14  
byte m_bEnableShadows = 0x0B18  
## [CSun]    
int m_clrRender = 0x0070  
int m_clrOverlay = 0x0B38  
Vector m_vDirection = 0x0B44  
byte m_bOn = 0x0B50  
int m_nSize = 0x0B3C  
int m_nOverlaySize = 0x0B40  
int m_nMaterial = 0x0B54  
int m_nOverlayMaterial = 0x0B58  
float HDRColorScale = 0x0000  
float glowDistanceScale = 0x0000  
## [CParticlePerformanceMonitor]    
byte m_bMeasurePerf = 0x09D9  
byte m_bDisplayPerf = 0x09D8  
## [CSpotlightEnd]    
float m_flLightScale = 0x09D8  
float m_Radius = 0x09DC  
## [CSpatialEntity]    
Vector m_vecOrigin = 0x09D8  
float m_minFalloff = 0x09E4  
float m_maxFalloff = 0x09E8  
float m_flCurWeight = 0x09EC  
byte m_bEnabled = 0x0AF4  
## [CSlideshowDisplay]    
byte m_bEnabled = 0x09D8  
char[128]     m_szDisplayText = 0x09D9  
char[128]     m_szSlideshowDirectory = 0x0A59  
void* m_chCurrentSlideLists = 0x0AF0  
float m_fMinSlideTime = 0x0B08  
float m_fMaxSlideTime = 0x0B0C  
int m_iCycleType = 0x0B14  
byte m_bNoListRepeats = 0x0B18  
## [CShadowControl]    
Vector m_shadowDirection = 0x09D8  
int m_shadowColor = 0x09E4  
float m_flShadowMaxDist = 0x09E8  
byte m_bDisableShadows = 0x09EC  
byte m_bEnableLocalLightShadows = 0x09ED  
## [CSceneEntity]    
int m_nSceneStringIndex = 0x09E8  
byte m_bIsPlayingBack = 0x09DC  
byte m_bPaused = 0x09DD  
byte m_bMultiplayer = 0x09DE  
float m_flForceClientTime = 0x09E4  
void* m_hActorList = 0x0000  
## [CRopeKeyframe]    
int m_nChangeCount = 0x0CCC  
int m_iRopeMaterialModelIndex = 0x0A14  
int m_hStartPoint = 0x0CAC  
int m_hEndPoint = 0x0CB0  
short m_iStartAttachment = 0x0CB4  
short m_iEndAttachment = 0x0CB6  
int m_fLockedPoints = 0x0CC8  
int m_Slack = 0x0CC0  
int m_RopeLength = 0x0CBC  
int m_RopeFlags = 0x0A10  
float m_TextureScale = 0x0CC4  
int m_nSegments = 0x0CA8  
byte m_bConstrainBetweenEndpoints = 0x0D50  
int m_Subdiv = 0x0CB8  
float m_Width = 0x0CD0  
float m_flScrollSpeed = 0x0A0C  
Vector m_vecOrigin = 0x0138  
int moveparent = 0x0148  
byte m_iParentAttachment = 0x02EC  
int m_iDefaultRopeMaterialModelIndex = 0x0A18  
byte m_nMinCPULevel = 0x0988  
byte m_nMaxCPULevel = 0x0989  
byte m_nMinGPULevel = 0x098A  
byte m_nMaxGPULevel = 0x098B  
## [CRagdollManager]    
int m_iCurrentMaxRagdollCount = 0x09D8  
## [CPhysicsPropMultiplayer]    
int m_iPhysicsMode = 0x29D4  
float m_fMass = 0x29D8  
Vector m_collisionMins = 0x29DC  
Vector m_collisionMaxs = 0x29E8  
## [CPhysBoxMultiplayer]    
int m_iPhysicsMode = 0x09E4  
float m_fMass = 0x09E8  
## [CPropDoorRotating]    
## [CBasePropDoor]    
## [CDynamicProp]    
byte m_bUseHitboxesForRenderBox = 0x29B4  
float m_flGlowMaxDist = 0x29D4  
byte m_bShouldGlow = 0x29D8  
int m_clrGlow = 0x29D9  
int m_nGlowStyle = 0x29E0  
## [CProp_Hallucination]    
byte m_bEnabled = 0x29A9  
float m_fVisibleTime = 0x29AC  
float m_fRechargeTime = 0x29B0  
## [CPostProcessController]    
void* m_flPostProcessParameters = 0x09D8  
byte m_bMaster = 0x0A04  
## [CPointWorldText]    
char[260]     m_szText = 0x0A08  
float m_flTextSize = 0x0B0C  
int m_textColor = 0x0B10  
## [CPointCommentaryNode]    
byte m_bActive = 0x2990  
float m_flStartTime = 0x2994  
char[260]     m_iszCommentaryFile = 0x2998  
char[260]     m_iszCommentaryFileNoHDR = 0x2A9C  
char[256]     m_iszSpeakers = 0x2BA0  
int m_iNodeNumber = 0x2CA0  
int m_iNodeNumberMax = 0x2CA4  
int m_hViewPosition = 0x2CAC  
## [CPointCamera]    
float m_FOV = 0x09D8  
float m_Resolution = 0x09DC  
byte m_bFogEnable = 0x09E0  
int m_FogColor = 0x09E1  
float m_flFogStart = 0x09E8  
float m_flFogEnd = 0x09EC  
float m_flFogMaxDensity = 0x09F0  
byte m_bActive = 0x09F4  
byte m_bUseScreenAspectRatio = 0x09F5  
## [CPlayerResource]    
void* m_iPing = 0x0B28  
void* m_iKills = 0x0C2C  
void* m_iAssists = 0x0D30  
void* m_iDeaths = 0x0E34  
void* m_bConnected = 0x0AE4  
void* m_iTeam = 0x0F38  
void* m_iPendingTeam = 0x103C  
void* m_bAlive = 0x1140  
void* m_iHealth = 0x1184  
void* m_iCoachingTeam = 0x1288  
## [CPlasma]    
float m_flStartScale = 0x09D8  
float m_flScale = 0x09DC  
float m_flScaleTime = 0x09E0  
int m_nFlags = 0x09E4  
int m_nPlasmaModelIndex = 0x09E8  
int m_nPlasmaModelIndex2 = 0x09EC  
int m_nGlowModelIndex = 0x09F0  
## [CPhysMagnet]    
## [CPhysicsProp]    
byte m_bAwake = 0x29B0  
int m_spawnflags = 0x02C8  
## [CStatueProp]    
int m_hInitBaseAnimating = 0x29D0  
byte m_bShatter = 0x29D4  
int m_nShatterFlags = 0x29D8  
Vector m_vShatterPosition = 0x29DC  
Vector m_vShatterForce = 0x29E8  
## [CPhysBox]    
float m_mass = 0x09D8  
## [CParticleSystem]    
Vector m_vecOrigin = 0x0138  
int m_fEffects = 0x00F0  
int m_hOwnerEntity = 0x014C  
int moveparent = 0x0148  
byte m_iParentAttachment = 0x02EC  
Vector m_angRotation = 0x012C  
int m_iEffectIndex = 0x09D8  
byte m_bActive = 0x09E0  
int m_nStopType = 0x09DC  
float m_flStartTime = 0x09E4  
char[260]     m_szSnapshotFileName = 0x09E8  
void* m_vServerControlPoints = 0x0AEC  
void* m_iServerControlPointAssignments = 0x0B1C  
void* m_hControlPointEnts = 0x0B30  
void* m_iControlPointParents = 0x0C2C  
## [CMovieDisplay]    
byte m_bEnabled = 0x09D8  
byte m_bLooping = 0x09D9  
char[128]     m_szMovieFilename = 0x09DA  
char[128]     m_szGroupName = 0x0A5A  
byte m_bStretchToFill = 0x0ADA  
byte m_bForcedSlave = 0x0ADB  
byte m_bUseCustomUVs = 0x0ADC  
float m_flUMin = 0x0AE0  
float m_flUMax = 0x0AE4  
float m_flVMin = 0x0AE8  
float m_flVMax = 0x0AEC  
## [CMaterialModifyControl]    
char[255]     m_szMaterialName = 0x09D8  
char[255]     m_szMaterialVar = 0x0AD7  
char[255]     m_szMaterialVarValue = 0x0BD6  
int m_iFrameStart = 0x0CE0  
int m_iFrameEnd = 0x0CE4  
byte m_bWrap = 0x0CE8  
float m_flFramerate = 0x0CEC  
byte m_bNewAnimCommandsSemaphore = 0x0CF0  
float m_flFloatLerpStartValue = 0x0CF4  
float m_flFloatLerpEndValue = 0x0CF8  
float m_flFloatLerpTransitionTime = 0x0CFC  
byte m_bFloatLerpWrap = 0x0D00  
int m_nModifyMode = 0x0D08  
## [CLightGlow]    
int m_clrRender = 0x0070  
int m_nHorizontalSize = 0x09D8  
int m_nVerticalSize = 0x09DC  
int m_nMinDist = 0x09E0  
int m_nMaxDist = 0x09E4  
int m_nOuterMaxDist = 0x09E8  
int m_spawnflags = 0x09EC  
Vector m_vecOrigin = 0x0138  
Vector m_angRotation = 0x012C  
int moveparent = 0x0148  
float m_flGlowProxySize = 0x0AC4  
float HDRColorScale = 0x0000  
## [CItemAssaultSuitUseable]    
int m_nArmorValue = 0x3450  
byte m_bIsHeavyAssaultSuit = 0x3454  
## [CItem]    
byte m_bShouldGlow = 0x3240  
## [CInfoOverlayAccessor]    
byte m_iTextureFrameIndex = 0x098C  
int m_iOverlayID = 0x09D8  
## [CFuncTrackTrain]    
## [CFuncSmokeVolume]    
int m_Color1 = 0x0AC4  
int m_Color2 = 0x0AC8  
char[255]     m_MaterialName = 0x0ACC  
float m_ParticleDrawWidth = 0x0BCC  
float m_ParticleSpacingDistance = 0x0BD0  
float m_DensityRampSpeed = 0x0BD4  
float m_RotationSpeed = 0x0BD8  
float m_MovementSpeed = 0x0BDC  
float m_Density = 0x0BE0  
float m_maxDrawDistance = 0x0BE4  
int m_spawnflags = 0x0BE8  
## [CCollisionProperty]    
Vector m_vecMins = 0x0328  
Vector m_vecMaxs = 0x0334  
int m_nSolidType = 0x0342  
int m_usSolidFlags = 0x0340  
int m_nSurroundType = 0x034A  
int m_triggerBloat = 0x0343  
Vector m_vecSpecifiedSurroundingMins = 0x034C  
Vector m_vecSpecifiedSurroundingMaxs = 0x0358  
void* m_Collision = 0x0320  
## [CFuncRotating]    
Vector m_vecOrigin = 0x0138  
float m_angRotation[0]     = 0x012C  
float m_angRotation[1]     = 0x0130  
float m_angRotation[2]     = 0x0134  
int m_flSimulationTime = 0x0268  
## [CFuncReflectiveGlass]    
## [CFuncOccluder]    
byte m_bActive = 0x09DC  
int m_nOccluderIndex = 0x09D8  
## [CFuncMoveLinear]    
Vector m_vecVelocity = 0x0114  
int m_fFlags = 0x0104  
## [CFuncMonitor]    
## [CFunc_LOD]    
int m_nDisappearMinDist = 0x09D8  
int m_nDisappearMaxDist = 0x09DC  
## [CTEDust]    
float m_flSize = 0x001C  
float m_flSpeed = 0x0020  
Vector m_vecDirection = 0x0024  
## [CFunc_Dust]    
int m_Color = 0x09D8  
int m_SpawnRate = 0x09DC  
float m_flSizeMin = 0x09E0  
float m_flSizeMax = 0x09E4  
int m_LifetimeMin = 0x09EC  
int m_LifetimeMax = 0x09F0  
int m_DustFlags = 0x0A00  
int m_SpeedMax = 0x09E8  
int m_DistMax = 0x09F4  
short m_nModelIndex = 0x0258  
float m_FallSpeed = 0x09F8  
byte m_bAffectedByWind = 0x09FC  
## [CCollisionProperty]    
Vector m_vecMins = 0x0328  
Vector m_vecMaxs = 0x0334  
int m_nSolidType = 0x0342  
int m_usSolidFlags = 0x0340  
int m_nSurroundType = 0x034A  
int m_triggerBloat = 0x0343  
Vector m_vecSpecifiedSurroundingMins = 0x034C  
Vector m_vecSpecifiedSurroundingMaxs = 0x0358  
void* m_Collision = 0x0320  
## [CFuncConveyor]    
float m_flConveyorSpeed = 0x09D8  
## [CFuncBrush]    
## [CBreakableSurface]    
int m_nNumWide = 0x09DC  
int m_nNumHigh = 0x09E0  
float m_flPanelWidth = 0x09E4  
float m_flPanelHeight = 0x09E8  
Vector m_vNormal = 0x09EC  
Vector m_vCorner = 0x09F8  
byte m_bIsBroken = 0x0A04  
int m_nSurfaceType = 0x0A08  
void* m_RawPanelBitVec = 0x0A2C  
## [CFuncAreaPortalWindow]    
float m_flFadeStartDist = 0x09D8  
float m_flFadeDist = 0x09DC  
float m_flTranslucencyLimit = 0x09E0  
int m_iBackgroundModelIndex = 0x09E4  
## [CCFish]    
Vector m_poolOrigin = 0x29F0  
float m_x = 0x29D8  
float m_y = 0x29DC  
float m_z = 0x29E0  
float m_angle = 0x29E8  
short m_nModelIndex = 0x0258  
byte m_lifeState = 0x025F  
float m_waterLevel = 0x29FC  
## [CFireSmoke]    
float m_flStartScale = 0x09D8  
float m_flScale = 0x09DC  
float m_flScaleTime = 0x09E0  
int m_nFlags = 0x09E4  
int m_nFlameModelIndex = 0x09E8  
int m_nFlameFromAboveModelIndex = 0x09EC  
## [CEnvTonemapController]    
byte m_bUseCustomAutoExposureMin = 0x09D8  
byte m_bUseCustomAutoExposureMax = 0x09D9  
byte m_bUseCustomBloomScale = 0x09DA  
float m_flCustomAutoExposureMin = 0x09DC  
float m_flCustomAutoExposureMax = 0x09E0  
float m_flCustomBloomScale = 0x09E4  
float m_flCustomBloomScaleMinimum = 0x09E8  
float m_flBloomExponent = 0x09EC  
float m_flBloomSaturation = 0x09F0  
float m_flTonemapPercentTarget = 0x09F4  
float m_flTonemapPercentBrightPixels = 0x09F8  
float m_flTonemapMinAvgLum = 0x09FC  
float m_flTonemapRate = 0x0A00  
## [CEnvScreenEffect]    
float m_flDuration = 0x09D8  
int m_nType = 0x09DC  
## [CEnvScreenOverlay]    
char[255]     m_iszOverlayNames[0]     = 0x09D8  
array[10]     m_iszOverlayNames = 0x0000  
float m_flOverlayTimes[0]     = 0x13D0  
array[10]     m_flOverlayTimes = 0x0000  
float m_flStartTime = 0x13F8  
int m_iDesiredOverlay = 0x13FC  
byte m_bIsActive = 0x1400  
## [CEnvProjectedTexture]    
int m_hTargetEntity = 0x09DC  
byte m_bState = 0x09E0  
byte m_bAlwaysUpdate = 0x09E1  
float m_flLightFOV = 0x09E4  
byte m_bEnableShadows = 0x09E8  
byte m_bSimpleProjection = 0x09E9  
byte m_bLightOnlyTarget = 0x09EA  
byte m_bLightWorld = 0x09EB  
byte m_bCameraSpace = 0x09EC  
float m_flBrightnessScale = 0x09F0  
int m_LightColor = 0x09F4  
float m_flColorTransitionTime = 0x0A08  
float m_flAmbient = 0x0A0C  
char[260]     m_SpotlightTextureName = 0x0A18  
int m_nSpotlightTextureFrame = 0x0B24  
float m_flNearZ = 0x0A10  
float m_flFarZ = 0x0A14  
int m_nShadowQuality = 0x0B28  
float m_flProjectionSize = 0x0B38  
float m_flRotation = 0x0B3C  
int m_iStyle = 0x0B2C  
## [CEnvParticleScript]    
float m_flSequenceScale = 0x2A74  
## [CFogController]    
byte m_fog.enable = 0x0A1C  
byte m_fog.blend = 0x0A1D  
Vector m_fog.dirPrimary = 0x09DC  
int m_fog.colorPrimary = 0x09E8  
int m_fog.colorSecondary = 0x09EC  
float m_fog.start = 0x09F8  
float m_fog.end = 0x09FC  
float m_fog.farz = 0x0A00  
float m_fog.maxdensity = 0x0A04  
int m_fog.colorPrimaryLerpTo = 0x09F0  
int m_fog.colorSecondaryLerpTo = 0x09F4  
float m_fog.startLerpTo = 0x0A08  
float m_fog.endLerpTo = 0x0A0C  
float m_fog.maxdensityLerpTo = 0x0A10  
float m_fog.lerptime = 0x0A14  
float m_fog.duration = 0x0A18  
float m_fog.HDRColorScale = 0x0A24  
float m_fog.ZoomFogScale = 0x0A20  
## [CEnvDOFController]    
byte m_bDOFEnabled = 0x09D8  
float m_flNearBlurDepth = 0x09DC  
float m_flNearFocusDepth = 0x09E0  
float m_flFarFocusDepth = 0x09E4  
float m_flFarBlurDepth = 0x09E8  
float m_flNearBlurRadius = 0x09EC  
float m_flFarBlurRadius = 0x09F0  
## [CCascadeLight]    
Vector m_shadowDirection = 0x09D8  
Vector m_envLightShadowDirection = 0x09E4  
byte m_bEnabled = 0x09F0  
byte m_bUseLightEnvAngles = 0x09F1  
int m_LightColor = 0x09F2  
int m_LightColorScale = 0x09F8  
float m_flMaxShadowDist = 0x09FC  
## [CEnvAmbientLight]    
Vector m_vecColor = 0x0B00  
## [CEntityParticleTrail]    
int m_iMaterialName = 0x0AC0  
## [CEntityParticleTrailInfo]    
float m_flLifetime = 0x0ACC  
float m_flStartSize = 0x0AD0  
float m_flEndSize = 0x0AD4  
void* m_Info = 0x0AC4  
int m_hConstraintEntity = 0x0AD8  
## [CEntityFreezing]    
Vector m_vFreezingOrigin = 0x09D8  
void* m_flFrozenPerHitbox = 0x09E4  
float m_flFrozen = 0x0AAC  
byte m_bFinishFreezing = 0x0AB0  
## [CEntityFlame]    
int m_hEntAttached = 0x09D8  
byte m_bCheapEffect = 0x09EC  
## [CEntityDissolve]    
float m_flStartTime = 0x09DC  
float m_flFadeOutStart = 0x09E0  
float m_flFadeOutLength = 0x09E4  
float m_flFadeOutModelStart = 0x09E8  
float m_flFadeOutModelLength = 0x09EC  
float m_flFadeInStart = 0x09F0  
float m_flFadeInLength = 0x09F4  
int m_nDissolveType = 0x09F8  
Vector m_vDissolverOrigin = 0x0A00  
int m_nMagnitude = 0x0A0C  
## [CDynamicLight]    
byte m_Flags = 0x09D8  
byte m_LightStyle = 0x09D9  
float m_Radius = 0x09DC  
int m_Exponent = 0x09E0  
float m_InnerAngle = 0x09E4  
float m_OuterAngle = 0x09E8  
float m_SpotRadius = 0x09EC  
## [CColorCorrectionVolume]    
byte m_bEnabled = 0x0A20  
float m_MaxWeight = 0x0A24  
float m_FadeDuration = 0x0A28  
float m_Weight = 0x0A2C  
char[260]     m_lookupFilename = 0x0A30  
## [CColorCorrection]    
Vector m_vecOrigin = 0x09D8  
float m_minFalloff = 0x09E4  
float m_maxFalloff = 0x09E8  
float m_flCurWeight = 0x09F8  
float m_flMaxWeight = 0x09F4  
float m_flFadeInDuration = 0x09EC  
float m_flFadeOutDuration = 0x09F0  
char[260]     m_netLookupFilename = 0x09FC  
byte m_bEnabled = 0x0B00  
byte m_bMaster = 0x0B01  
byte m_bClientSide = 0x0B02  
byte m_bExclusive = 0x0B03  
## [CBreakableProp]    
Vector m_qPreferredPlayerCarryAngles = 0x2994  
byte m_bClientPhysics = 0x29A0  
## [CBeamSpotlight]    
int m_nHaloIndex = 0x09D8  
byte m_bSpotlightOn = 0x09E4  
byte m_bHasDynamicLight = 0x09E5  
float m_flSpotlightMaxLength = 0x09E8  
float m_flSpotlightGoalWidth = 0x09EC  
float m_flHDRColorScale = 0x09F0  
int m_nRotationAxis = 0x09DC  
float m_flRotationSpeed = 0x09E0  
## [CBaseButton]    
byte m_usable = 0x0A08  
## [CBaseToggle]    
Vector m_vecFinalDest = 0x09EC  
int m_movementType = 0x09F8  
float m_flMoveTargetTime = 0x09FC  
## [CBasePlayer]    
## [CLocalPlayerExclusive]    
## [CLocal]    
void* m_chAreaBits = 0x2FD0  
void* m_chAreaPortalBits = 0x2FF0  
int m_iHideHUD = 0x3014  
float m_flFOVRate = 0x3010  
byte m_bDucked = 0x3054  
byte m_bDucking = 0x3055  
float m_flLastDuckTime = 0x3058  
byte m_bInDuckJump = 0x305C  
int m_nDuckTimeMsecs = 0x3018  
int m_nDuckJumpTimeMsecs = 0x301C  
int m_nJumpTimeMsecs = 0x3020  
float m_flFallVelocity = 0x3024  
Vector m_viewPunchAngle = 0x3030  
Vector m_aimPunchAngle = 0x303C  
Vector m_aimPunchAngleVel = 0x3048  
byte m_bDrawViewmodel = 0x305D  
byte m_bWearingSuit = 0x305E  
byte m_bPoisoned = 0x305F  
float m_flStepSize = 0x302C  
byte m_bAllowAutoMovement = 0x3060  
int m_skybox3d.scale = 0x3100  
Vector m_skybox3d.origin = 0x3104  
int m_skybox3d.area = 0x3110  
byte m_skybox3d.fog.enable = 0x3158  
byte m_skybox3d.fog.blend = 0x3159  
Vector m_skybox3d.fog.dirPrimary = 0x3118  
int m_skybox3d.fog.colorPrimary = 0x3124  
int m_skybox3d.fog.colorSecondary = 0x3128  
float m_skybox3d.fog.start = 0x3134  
float m_skybox3d.fog.end = 0x3138  
float m_skybox3d.fog.maxdensity = 0x3140  
float m_skybox3d.fog.HDRColorScale = 0x3160  
Vector m_audio.localSound[0]     = 0x3168  
Vector m_audio.localSound[1]     = 0x3174  
Vector m_audio.localSound[2]     = 0x3180  
Vector m_audio.localSound[3]     = 0x318C  
Vector m_audio.localSound[4]     = 0x3198  
Vector m_audio.localSound[5]     = 0x31A4  
Vector m_audio.localSound[6]     = 0x31B0  
Vector m_audio.localSound[7]     = 0x31BC  
int m_audio.soundscapeIndex = 0x31C8  
int m_audio.localBits = 0x31CC  
int m_audio.entIndex = 0x31D0  
void* m_Local = 0x2FCC  
float m_vecViewOffset[0]     = 0x0108  
float m_vecViewOffset[1]     = 0x010C  
float m_vecViewOffset[2]     = 0x0110  
float m_flFriction = 0x0144  
byte m_fOnTarget = 0x3334  
int m_nTickBase = 0x3440  
int m_nNextThinkTick = 0x00FC  
int m_hLastWeapon = 0x3304  
float m_vecVelocity[0]     = 0x0114  
float m_vecVelocity[1]     = 0x0118  
float m_vecVelocity[2]     = 0x011C  
Vector m_vecBaseVelocity = 0x0120  
int m_hConstraintEntity = 0x3354  
Vector m_vecConstraintCenter = 0x3358  
float m_flConstraintRadius = 0x3364  
float m_flConstraintWidth = 0x3368  
float m_flConstraintSpeedFactor = 0x336C  
byte m_bConstraintPastRadius = 0x3370  
float m_flDeathTime = 0x33D4  
float m_flNextDecalTime = 0x33D8  
float m_fForceTeam = 0x33DC  
float m_flLaggedMovementValue = 0x35A4  
int m_hTonemapController = 0x31DC  
void* localdata = 0x0000  
## [CPlayerState]    
byte deadflag = 0x31E4  
void* pl = 0x31E0  
int m_iFOV = 0x31F4  
int m_iFOVStart = 0x31F8  
float m_flFOVTime = 0x3218  
int m_iDefaultFOV = 0x333C  
int m_hZoomOwner = 0x325C  
int m_afPhysicsFlags = 0x32FC  
int m_hVehicle = 0x3300  
int m_hUseEntity = 0x3338  
int m_hGroundEntity = 0x0150  
int m_iHealth = 0x0100  
byte m_lifeState = 0x025F  
void* m_iAmmo = 0x2D88  
int m_iBonusProgress = 0x3250  
int m_iBonusChallenge = 0x3254  
float m_flMaxspeed = 0x3258  
int m_fFlags = 0x0104  
int m_iObserverMode = 0x3388  
byte m_bActiveCameraMan = 0x338C  
byte m_bCameraManXRay = 0x338D  
byte m_bCameraManOverview = 0x338E  
byte m_bCameraManScoreBoard = 0x338F  
byte m_uCameraManGraphs = 0x3390  
int m_iDeathPostEffect = 0x3384  
int m_hObserverTarget = 0x339C  
int m_hViewModel[0]     = 0x3308  
array[3]     m_hViewModel = 0x0000  
int m_iCoachingTeam = 0x2F60  
char[18]     m_szLastPlaceName = 0x35C4  
Vector m_vecLadderNormal = 0x3240  
int m_ladderSurfaceProps = 0x3210  
byte m_ubEFNoInterpParity = 0x35E8  
int m_hPostProcessCtrl = 0x37B8  
int m_hColorCorrectionCtrl = 0x37BC  
int m_PlayerFog.m_hCtrl = 0x37C4  
int m_vphysicsCollisionState = 0x326C  
int m_hViewEntity = 0x334C  
byte m_bShouldDrawPlayerWhileUsingViewEntity = 0x3350  
float m_flDuckAmount = 0x2FBC  
float m_flDuckSpeed = 0x2FC0  
byte m_nWaterLevel = 0x025E  
## [CBaseFlex]    
void* m_flexWeight = 0x2A38  
int m_blinktoggle = 0x2BE4  
Vector m_viewtarget = 0x2A00  
## [CBaseEntity]    
## [CAnimTimeMustBeFirst]    
int m_flAnimTime = 0x0260  
void* AnimTimeMustBeFirst = 0x0000  
int m_flSimulationTime = 0x0268  
int m_cellbits = 0x0074  
int m_cellX = 0x007C  
int m_cellY = 0x0080  
int m_cellZ = 0x0084  
Vector m_vecOrigin = 0x0138  
Vector m_angRotation = 0x012C  
short m_nModelIndex = 0x0258  
int m_fEffects = 0x00F0  
byte m_nRenderMode = 0x025B  
byte m_nRenderFX = 0x025A  
int m_clrRender = 0x0070  
int m_iTeamNum = 0x00F4  
int m_iPendingTeamNum = 0x00F8  
int m_CollisionGroup = 0x0474  
float m_flElasticity = 0x0300  
float m_flShadowCastDistance = 0x03A0  
int m_hOwnerEntity = 0x014C  
int m_hEffectEntity = 0x0998  
int moveparent = 0x0148  
byte m_iParentAttachment = 0x02EC  
char[260]     m_iName = 0x0154  
int movetype = 0x0000  
int movecollide = 0x0000  
## [CCollisionProperty]    
Vector m_vecMins = 0x0328  
Vector m_vecMaxs = 0x0334  
int m_nSolidType = 0x0342  
int m_usSolidFlags = 0x0340  
int m_nSurroundType = 0x034A  
int m_triggerBloat = 0x0343  
Vector m_vecSpecifiedSurroundingMins = 0x034C  
Vector m_vecSpecifiedSurroundingMaxs = 0x0358  
void* m_Collision = 0x0320  
byte m_iTextureFrameIndex = 0x098C  
int m_bSimulatedEveryTick = 0x093A  
int m_bAnimatedEveryTick = 0x093B  
byte m_bAlternateSorting = 0x093C  
int m_bSpotted = 0x093D  
void* m_bSpottedBy = 0x093E  
void* m_bSpottedByMask = 0x0980  
byte m_bIsAutoaimTarget = 0x0060  
float m_fadeMinDist = 0x02F4  
float m_fadeMaxDist = 0x02F8  
float m_flFadeScale = 0x02FC  
byte m_nMinCPULevel = 0x0988  
byte m_nMaxCPULevel = 0x0989  
byte m_nMinGPULevel = 0x098A  
byte m_nMaxGPULevel = 0x098B  
float m_flUseLookAtAngle = 0x02CC  
float m_flLastMadeNoiseTime = 0x0020  
float m_flMaxFallVelocity = 0x00DC  
byte m_bEligibleForScreenHighlight = 0x09B9  
## [CBaseDoor]    
float m_flWaveHeight = 0x0A08  
## [CBaseCombatCharacter]    
## [CBCCLocalPlayerExclusive]    
float m_flNextAttack = 0x2D80  
void* bcc_localdata = 0x0000  
## [CBCCNonLocalPlayerExclusive]    
void* m_hMyWeapons = 0x2E08  
void* bcc_nonlocaldata = 0x0000  
int m_LastHitGroup = 0x2D84  
int m_hActiveWeapon = 0x2F08  
float m_flTimeOfLastInjury = 0x2F0C  
int m_nRelativeDirectionOfLastInjury = 0x2F10  
void* m_hMyWearables = 0x2F14  
## [CBaseAnimatingOverlay]    
## [COverlayVars]    
void* m_AnimOverlay = 0x0000  
void* overlay_vars = 0x0000  
## [CBoneFollower]    
int m_modelIndex = 0x09D8  
int m_solidIndex = 0x09DC  
## [CBaseAnimating]    
int m_nSequence = 0x28C0  
int m_nForceBone = 0x268C  
Vector m_vecForce = 0x2680  
int m_nSkin = 0x0A1C  
int m_nBody = 0x0A20  
int m_nHitboxSet = 0x09FC  
float m_flModelScale = 0x274C  
void* m_flPoseParameter = 0x2778  
float m_flPlaybackRate = 0x0A18  
void* m_flEncodedController = 0x0A54  
byte m_bClientSideAnimation = 0x28A0  
byte m_bClientSideFrameReset = 0x26C4  
byte m_bClientSideRagdoll = 0x0279  
int m_nNewSequenceParity = 0x0A44  
int m_nResetEventsParity = 0x0A48  
byte m_nMuzzleFlashParity = 0x0A64  
int m_hLightingOrigin = 0x2948  
## [CServerAnimationData]    
float m_flCycle = 0x0A14  
void* serveranimdata = 0x0000  
float m_flFrozen = 0x26FC  
int m_ScaleType = 0x2750  
byte m_bSuppressAnimSounds = 0x294E  
int m_nHighlightColorR = 0x0A38  
int m_nHighlightColorG = 0x0A3C  
int m_nHighlightColorB = 0x0A40  
## [CAI_BaseNPC]    
byte m_lifeState = 0x025F  
byte m_bPerformAvoidance = 0x2F34  
byte m_bIsMoving = 0x2F35  
byte m_bFadeCorpse = 0x2F36  
int m_iDeathPose = 0x2F24  
int m_iDeathFrame = 0x2F28  
int m_iSpeedModRadius = 0x2F2C  
int m_iSpeedModSpeed = 0x2F30  
byte m_bSpeedModActive = 0x2F37  
byte m_bImportanRagdoll = 0x2F38  
float m_flTimePingEffect = 0x2F20  
## [CBeam]    
int m_nBeamType = 0x09F4  
int m_nBeamFlags = 0x09F8  
int m_nNumBeamEnts = 0x09E8  
void* m_hAttachEntity = 0x09FC  
void* m_nAttachIndex = 0x0A24  
int m_nHaloIndex = 0x09F0  
float m_fHaloScale = 0x0A58  
float m_fWidth = 0x0A4C  
float m_fEndWidth = 0x0A50  
float m_fFadeLength = 0x0A54  
float m_fAmplitude = 0x0A5C  
float m_fStartFrame = 0x0A60  
float m_fSpeed = 0x0A64  
float m_flFrameRate = 0x09D8  
float m_flHDRColorScale = 0x09DC  
int m_clrRender = 0x0070  
byte m_nRenderFX = 0x025A  
byte m_nRenderMode = 0x025B  
float m_flFrame = 0x0A68  
int m_nClipStyle = 0x0A6C  
Vector m_vecEndPos = 0x0A70  
short m_nModelIndex = 0x0258  
Vector m_vecOrigin = 0x0138  
int moveparent = 0x0148  
## [CBaseViewModel]    
int m_nModelIndex = 0x0258  
int m_hWeapon = 0x29D8  
int m_nSkin = 0x0A1C  
int m_nBody = 0x0A20  
int m_nSequence = 0x28C0  
int m_nViewModelIndex = 0x29D0  
float m_flPlaybackRate = 0x0A18  
int m_fEffects = 0x00F0  
int m_nAnimationParity = 0x29D4  
int m_hOwner = 0x29DC  
int m_nNewSequenceParity = 0x0A44  
int m_nResetEventsParity = 0x0A48  
byte m_nMuzzleFlashParity = 0x0A64  
byte m_bShouldIgnoreOffsetAndAccuracy = 0x29A0  
## [CBaseParticleEntity]    
## [CBaseGrenade]    
float m_flDamage = 0x29A8  
float m_DmgRadius = 0x2994  
byte m_bIsLive = 0x2991  
int m_hThrower = 0x29B0  
Vector m_vecVelocity = 0x0114  
int m_fFlags = 0x0104  
## [CBaseCombatWeapon]    
## [CLocalWeaponData]    
int m_iPrimaryAmmoType = 0x326C  
int m_iSecondaryAmmoType = 0x3270  
int m_nViewModelIndex = 0x3244  
byte m_bFlipViewModel = 0x32D4  
int m_iWeaponOrigin = 0x32D8  
int m_iWeaponModule = 0x325C  
void* LocalWeaponData = 0x0000  
## [CLocalActiveWeaponData]    
float m_flNextPrimaryAttack = 0x3248  
float m_flNextSecondaryAttack = 0x324C  
int m_nNextThinkTick = 0x00FC  
float m_flTimeWeaponIdle = 0x3284  
void* LocalActiveWeaponData = 0x0000  
int m_iViewModelIndex = 0x3250  
int m_iWorldModelIndex = 0x3254  
int m_iWorldDroppedModelIndex = 0x3258  
int m_iState = 0x3268  
int m_hOwner = 0x3240  
int m_iClip1 = 0x3274  
int m_iClip2 = 0x3278  
int m_iPrimaryReserveAmmoCount = 0x327C  
int m_iSecondaryReserveAmmoCount = 0x3280  
int m_hWeaponWorldModel = 0x3264  
int m_iNumEmptyAttacks = 0x3260  
## [CBaseWeaponWorldModel]    
int m_nModelIndex = 0x0258  
int m_nBody = 0x0A20  
int m_fEffects = 0x00F0  
int moveparent = 0x0148  
int m_hCombatWeaponParent = 0x2A00  