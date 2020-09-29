# Delphi 2010

- Enhanced RTTI (Run Time Type Information)
- Attributes
- Class Constructor/Destructor
- Support for Windows 7 Direct2D
- Touch screen and gestures
- Source code formatter
- Source code audits and metrics
- Source code for MIDAS.DLL
- Background compilation
- The as operator can be used to cast an interface reference back to the object from which it was extracted
- The is operator can be used to verify whether an interface reference was extracted from a certain class
- Normal unsafe casting can be performed on an interface: TObject(SomeInterface)
- new delayed directive indicates that an external library such as a DLL is not to be loaded at declaration time but is to wait until the first call to the method
