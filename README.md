# UnconfuserExTools
A repository containing tools used for unpacking and deobfuscating .NET applications protected with ConfuserEx

### WARNING: These tools have been aggragated from multiple sources around the web. These tools are provided as-is, and there is no guarantee on the safety of the file(s). It is recommended to run them in a sandboxed environment. 

## What is this?
This repository contains tools used in the unpacking and deobfuscation of .NET applications protected with ConfuserEx.

## How to use?
1. Run `NoFuserEx.exe`. This removes anti-tamper, anti-dumper, anti-debugger, and other protections.
2. Run `ConfuseExConstantDecryptor.exe`
3. Run `ConfuseExCallFixer.exe`
4. Run `ConfuseExDopPopPatcher.exe`
5. Run `ConfuseExExpressionKiller.exe`
6. Run `ConfuseExFixer.exe`
7. Run `ConfuseExSwitchKiller.exe` (might crash)
8. If SwitchKiller crashes, you can try `Proxy Call Fix v2`
8. Clean up with `de4dot`
9. Open the executable in `dnSpy`

## Sources
https://youtu.be/X0F_-sE-6GU
https://github.com/CodeShark-Dev/NoFuserEx

## Other possibly helpful tools
Here are some other tools that might be helpful. They could also entirely replace the tools in this list. I need to test more with them.
https://github.com/ViRb3/de4dot-cex
https://github.com/BedTheGod/ConfuserEx-Unpacker-Mod-by-Bed/tree/1.1

