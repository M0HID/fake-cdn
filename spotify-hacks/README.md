How to use
------

* Get original Spotify ipa from iTunes
* Rename App file extension .ipa to .zip and Extract
* Open main App Executable(like: Payload/AppName.app/AppName) on any Hex Editor
* Replece all occurencies of string "/usr/lib/libSystem.B.dylib" to "@executable_path/Sys.dylib" and Save Changes
* Copy file Sys.dylib to same Dir of App Executable(like: Payload/AppName.app/)
* Compress back to zip and rename compressed file extension .zip to .ipa
* Use [Altstore](https://altstore.io) to sign and install.
