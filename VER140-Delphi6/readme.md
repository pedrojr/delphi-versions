# Delphi 6

- dbExpress
- SOAP Web Services
- TCustomVariantType provides operator overloading for custom variant types
- New compiler directives (MSWINDOWS, LINUX, LIBPREFIX, LIBSUFFIX, LIBVERSION, MESSAGE '...', SetPEFlags)
- Support for {$IF}{$ELSE} compiler directives
- Compiler hinting directives: experimental, deprecated, library, platform (but without additional text for deprecated)
- Variant is no longer based on COM but changed to be CLX compatible, COM based variant renamed to OLEVariant
- Typed constants cannot be assigned to (Override with {$J+})
- Enumerated types can be assigned an explicit value (cf C++)
- Interface properties
- Support for calling varargs external functions (but only for the cdecl calling convention)
- Custom variants
