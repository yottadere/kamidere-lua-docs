# Render

Fonts by default has size 32, downscale will look fine, but sizes over 32 will be blurry.

## Functions

| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| void* | GetMainFont | () | - |
| void* | GetMainMediumFont | () | - |
| void* | GetIconsFont | () | - |
| Vector2D | CalcTextSize | (void* pFont, float flSize, string szText) | - |
| bool | WorldToScreen | (Vector vecPosition, OUT Vector2D& vecScreen) | - |
| void | EspBox | (Vector2D vecMin, Vector2D vecMax, Color color, float flEdgeFactor, bool bOutline) | - |
| void | Line | (Vector2D vecStart, Vector2D vecEnd, Color color, float flThickness) | - |
| void | Rect | (Vector2D vecMin, Vector2D vecMax, Color color, float flRounding, float flThickness, [ERectFlags](../enums/erectflags.md) flags, [ERoundCorners](../enums/eroundcorners.md) cornerFlags) | - |
| void | RectMultiColor | (Vector2D vecMin, Vector2D vecMax, Color colUpperLeft, Color colUpperRight, Color colBottomRight, Color colBottomLeft) | - |
| void | Polygon | (Vector2D vecPoints[], Color color, [EPolygonFlags](../enums/epolygonflags.md) flags, bool bClosed, float flThickness) | if bClosed is false you can use this as PolyLine |
| void | Circle | (Vector2D vecCenter, float flRadius, Color color, int nSegments, [ECircleFlags](../enums/ecircleflags.md) flags, float flThickness) | - |
| void | Text | (void* pFont, float flFontSize, Vector2D vecPosition, string szText, Color color, [ETextFlags](../enums/etextflags.md) flags, Color colorOutline) | - |
