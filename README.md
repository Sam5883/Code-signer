# Code-signer
Codesign or recodesign applications, other bundle types, and regular files like executables and DMGs.

### Features:
- Initial check for valid developer path (Xcode or Command Line Tools)
- Option to codesign in simple mode or deep mode (default: simple)● Option to select from code-signing certificates found in the user's keychains (only valid certificates)
- Automatic ad-hoc signature, if the user has no regular & valid code-signing certificate in his keychains
- Dequarantine operation before code-signing
- Automatic detritus removal on code-signing error
- Final code signature authority comparison besides internal error checks
- Support for signing many other types of files like Unix executables, disk images, sparsebundles, dynamic libraries, frameworks etc. (see also supported UTIs below)

### Dependencies: XCode and CLT    

Credits: Bucky