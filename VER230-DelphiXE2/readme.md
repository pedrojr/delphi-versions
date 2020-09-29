# Delphi XE2

- Cross platform support for Mac OSX (32-bit) and iOS
- Support for Win64
- Modified RTL to support cross platform (FireMonkey)
- Live Bindings (FireMonkey and VCL)
- DataSnap: Connectors for Mobile Devices, Cloud API, HTTPS support, TCP monitoring
- dbExpress support for ODBC drivers
- Packed Now Forces Byte Alignment of Records (Pre XE2 it did not necessarily do this)
- Eight new DEFINEs have been added: ALIGN_STACK, CPUX86, CPUX64, MACOS (Mac operating system), MACOS32, PC_MAPPED_EXCEPTIONS, PIC, WIN64
- Full unit scope names are now required in your uses clause
- {$ExcessPrecision on/off} compiler directive (x64 only)
- The build-in types differ depending on the target platform (32/64-bit)
- Extended Data Type Is 10 bytes on Win32, but 8 (!) bytes on Win64

## Links

http://docwiki.embarcadero.com/RADStudio/XE2/en/What%27s_New_in_Delphi_and_C++Builder_XE2
https://sourceforge.net/p/radstudiodemos/code/HEAD/tree/branches/RadStudio_XE2/
