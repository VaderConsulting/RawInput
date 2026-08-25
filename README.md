# RawInput

This is a C# WinForms working copy of a WM_INPUT keyboard library (`RawInput_dll`) plus a Keyboard demo host. The library registers for HID keyboard notifications, enumerates devices, and raises KeyPressed with handle, type, VKey, and press state. The Keyboard exe shows those fields on a form and writes DeviceAudit.txt. Assembly copyright is HOME 2008 on the library and 2013 on the demo. This is Dave Robinson's Historical Dev copy, not original VaderConsulting code.

**Source last updated:** 2017-03-21  
**Language:** C#  
**Target:** .NET 4.5  
**Output:** class library + WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `RawInput` | C# | class library (.NET 4.5) | `RawInput` NativeWindow wrapper around WM_INPUT keyboards |
| `Keyboard` | C# | WinForms exe (.NET 4.5) | Demo form listing device handle, VKey, and key state |

## How to open

Open `RawStuff.sln` in Visual Studio 2012 or later (targeting .NET 4.5). Run the Keyboard project.

## Attribution and provenance

From Dave Robinson's Historical Dev archive (OneDrive folder `RawInput`). Library assembly copyright HOME 2008; Keyboard demo copyright 2013. See `THIRD_PARTY_NOTICES.md`.

## License

Third-party RawInput sample terms as included. Catalogue/wrapper files MIT License. Copyright (c) 2026 VaderConsulting.
