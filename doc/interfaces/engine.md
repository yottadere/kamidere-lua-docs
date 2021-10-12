# Engine

## Functions

| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| Vector2D | GetScreenSize | () | - |
| [PlayerInfo](../classes/playerinfo.md) | GetPlayerInfo | (int nEntityIndex) | - |
| int | GetPlayerForUserID | (int nUserID) | - |
| bool | IsConsoleVisible | () | - |
| int | GetLocalPlayer | () | - |
| float | GetLastTimeStamp | () | - |
| QAngle | GetViewAngles | () | - |
| void | SetViewAngles | (QAngle angView) | - |
| int | GetMaxClients | () | - |
| [INetChannelInfo](../classes/inetchannelinfo.md)* | GetNetChannelInfo | () | - |
| bool | IsInGame | () | - |
| bool | IsConnected | () | - |
| string | GetLevelName | () | - |
| string | GetLevelNameShort | () | - |
| bool | IsPlayingDemo | () | - |
| bool | IsRecordingDemo | () | - |
| bool | IsPlayingTimeDemo | () | - |
| bool | IsTakingScreenshot | () | - |
| bool | IsHLTV | () | - |
| int | GetEngineBuildNumber | () | - |
| void | ExecuteClientCmd | (string szCmdString) | - |
| int | ClientCmdUnrestricted | (string szCmdString, bool bFromConsoleOrKeybind) | - |
| bool | IsVoiceRecording | () | - |