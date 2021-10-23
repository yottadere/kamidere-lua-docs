# Color

## Constructors

| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| [Color](../datatypes/color.md) | new | (float r, float g, float b, float a) | float values from 0.0 to 1.0 |

## Fields

| Type | Name | Description |
| :--- | :--- | :--- |
| float | r | - |
| float | g | - |
| float | b | - |
| float | a | - |

## Static functions

| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| [Color](../datatypes/color.md) | FromRGBA | (int r, int g, int b, int a) | int values from 0 to 255 |
| [Color](../datatypes/color.md) | FromHSB | (float flHue, float flSaturation, float flBrightness, float flAlpha) | - |
| float | GetHue | ([Color](../datatypes/color.md) color) | - |

```lua
-- from static
local colorWhite = Color.FromRGBA(255, 255, 255, 255)

-- from constructor
local colorBlack = Color.new(0.0, 0.0, 0.0, 1.0)
```