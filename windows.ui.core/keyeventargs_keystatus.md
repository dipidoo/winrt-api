---
-api-id: P:Windows.UI.Core.KeyEventArgs.KeyStatus
-api-type: winrt property
---

<!-- Property syntax
public Windows.UI.Core.CorePhysicalKeyStatus KeyStatus { get; }
-->

# Windows.UI.Core.KeyEventArgs.KeyStatus

## -description
Gets the status of a key at the time the event is fired.

## -property-value
The status of the key.

## -remarks
> **Windows 10**
> Apps do not receive this event when an [Input Method Editor (IME)](http://msdn.microsoft.com/library/5fcc73e6-f499-47e6-8e81-0014ca4d241c) is enabled. The Input Method Editor (IME) handles all keyboard input and sets [Handled](keyeventargs_handled.md) to **true**.

> **Windows Phone**
> This API is supported in native apps only.

## -examples

## -see-also
[KeyDown](corewindow_keydown.md), [KeyUp](corewindow_keyup.md)