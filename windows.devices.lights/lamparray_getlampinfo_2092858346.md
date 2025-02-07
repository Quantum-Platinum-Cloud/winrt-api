---
-api-id: M:Windows.Devices.Lights.LampArray.GetLampInfo(System.Int32)
-api-type: winrt method
ms.custom: RS5
---

<!-- Method syntax.
public LampInfo LampArray.GetLampInfo(Int32 lampIndex)
-->

# Windows.Devices.Lights.LampArray.GetLampInfo

## -description
Fetches the [LampInfo](lampinfo.md) corresponding to the lamp index.

## -parameters
### -param lampIndex
The index. Must be between 0 and [LampCount](lamparray_lampcount.md) - 1.

## -returns
The [LampInfo](lampinfo.md) corresponding to lampIndex.

## -remarks
The [LampInfo](lampinfo.md) contains properties about a lamp of a given index.

## -see-also

[Dynamic lighting](/windows/uwp/devices-sensors/lighting-dynamic-lamparray)


## -examples

[AutoRGB Sample](https://github.com/microsoft/Dynamic-Lighting-AutoRGB)

Demonstrates how to extract a single, representative color from a desktop screen and use it to illuminate LED lamps on a connected RGB device.
