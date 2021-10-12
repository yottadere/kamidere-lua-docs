# QAngle

## Constructors

| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| QAngle | new | (float x, float y, float z) | - |

## Fields

| Type | Name | Description |
| :--- | :--- | :--- |
| float | x | pitch |
| float | y | yaw |
| float | z | roll |

## Functions

| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| bool | IsEqual | (QAngle angCompare) | - |
| bool | IsZero | () | - |
| float | Length | () | - |
| float | Length2D | () | - |
| float | DistTo | (Vector vecTo) | - |
| QAngle | Normalized | () | - |
| QAngle | MathNormalized | () | like Vector:Normalized() |
| QAngle | Clamp | () | clamp themself and return themself |