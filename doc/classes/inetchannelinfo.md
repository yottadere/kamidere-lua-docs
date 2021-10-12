# INetChannelInfo

## Functions

| Return | Name | Args | Description |
| :--- | :--- | :--- | :--- |
| string | GetName | () | - |
| string | GetAddress | () | - |
| float | GetTime | () | - |
| float | GetTimeConnected | () | - |
| int | GetBufferSize | () | - |
| int | GetDataRate | () | - |
| bool | IsLoopback | () | - |
| bool | IsTimingOut | () | - |
| bool | IsPlayback | () | - |
| float | GetLatency | ([EFlow](../enums/eflow.md) flow) | - |
| float | GetAvgLatency | ([EFlow](../enums/eflow.md) flow) | - |
| float | GetAvgLoss | ([EFlow](../enums/eflow.md) flow) | - |
| float | GetAvgChoke | ([EFlow](../enums/eflow.md) flow) | - |
| float | GetAvgData | ([EFlow](../enums/eflow.md) flow) | - |
| float | GetAvgPackets | ([EFlow](../enums/eflow.md) flow) | - |
| int | GetTotalData | ([EFlow](../enums/eflow.md) flow) | - |
| int | GetTotalPackets | ([EFlow](../enums/eflow.md) flow) | - |
| int | GetSequenceNr | ([EFlow](../enums/eflow.md) flow) | - |
| bool | IsValidPacket | ([EFlow](../enums/eflow.md) flow, int nFrame) | - |
| float | GetPacketTime | ([EFlow](../enums/eflow.md) flow, int nFrames) | - |
| int | GetPacketBytes | ([EFlow](../enums/eflow.md) flow, int nFrames, int group) | - |
| float | GetTimeSinceLastReceived | () | - |
| float | GetCommandInterpolationAmount | ([EFlow](../enums/eflow.md) flow, int nFrames) | - |
| float | GetTimeoutSeconds | () | - |