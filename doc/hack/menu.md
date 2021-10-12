# Menu

## Functions

| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| CMenu* | CreateWindow | (string szLabel, int nColumns) | columns must contains elements |
| bool | IsOpened | () | - |

## IMenuItem

| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| CCheckbox* | AddCheckbox | (string szLabel, bool bStartValue, function fnCallback) | callback is called when the value changes |
| CSliderFloat* | AddSliderFloat | (string szLabel, float flStartValue, float flMin, float flMax, function fnCallback [ESliderFlags](../enums/esliderflags.md) flags) | - |
| CSliderInt* | AddSliderInt | (string szLabel, float flStartValue, float flMin, float flMax, function fnCallback [ESliderFlags](../enums/esliderflags.md) flags) | - |
| CColorEdit* | AddColorEdit | (string szLabel, Color colStartValue, function fnCallback, [EColorEditFlags](../enums/ecoloreditflags.md)) | - |

## IControlItem\<elementType> : IMenuItem

#### CCheckbox is IControlItem\<bool>, CSliderFloat is IControlItem\<float>, etc...

| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| elementType | GetValue | () | - |
| void | SetValue | (elementType newValue) | - |
| void | SetTooltip | (string szTooltip) | tooltip which appears when you hover on element |

## CMenu : IMenuItem

| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| void | NextColumn | () | - |

Example code:

```lua
local window = Menu.CreateWindow("test", 2)

local mainCheckbox = window:AddCheckbox("main checkbox", false, function () 

end)

-- appears on hover
mainCheckbox:SetTooltip("right click to customize")

-- appears on right click
local childCheckbox = mainCheckbox:AddCheckbox("child checkbox", false, function ()

end)

window:NextColumn()
local mainSlider = window:AddSliderFloat("sliderfloat", 1.0, 0.0, 10.0, function ()

end, 0)
```