The comInterfaces package is generated via SCons.
The logic for this is in `comInterfaces_sconscript`, which uses `comtypes.gen` to read `*.tlb` 
files or via interface IDs.

The interface files have an ID named file (a GUID, followed by a version number) as well as a
"friendly name" file.

The "friendly name" file generated by comtypes is not consumed easily by tools and IDEs,
runtime logic is used to expose symbols.
To remedy this, the file is then processed by `comInterfaces_sconscript` to extract the module
name and replace the import statement with a more elaborate approach which includes a fallback
for the purposes of IDEs and tools.

Only UIAutomation.py is not generated, UIA has historically been updated regularly and the version on
Appveyor build servers could not be guaranteed.
