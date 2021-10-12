# Esp

## Functions

| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| void | AddText | (void* pFont, float flFontSize, [EspBounds](../datatypes/espbounds.md)* pBounds, string szText, Color color, [EDrawPosition](../enums/edrawposition.md) pos, [ETextFlags](../enums/etextflags.md) flags) | - |
| void | AddBar | ([EspBounds](../datatypes/espbounds.md)* pBounds, float flValue, float flMaxValue, Color color, [EDrawPosition](../enums/edrawposition.md) pos, bool bFixedSize, Vector2D vecSize) | if bFixedSize is true then bar will use vecSize |
