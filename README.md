# UnconfuserExTools
A repository containing tools used for unpacking and deobfuscating .NET applications protected with ConfuserEx

### WARNING: These tools have been aggragated from multiple sources around the web. These tools are provided as-is, and there is no guarantee on the safety of the file(s). It is recommended to run them in a sandboxed environment. 

## What is this?
This repository contains tools used in the unpacking and deobfuscation of .NET applications protected with ConfuserEx. I was analyzing a malware artifact protected by ConfuserEx, and most tutorials online referenced tools such as "UnconfuserEx" and "ConfuseExSwitchKiller", but links were dead / not readily available. I've created this repository to act as a centralized place for all tools related to the deobfuscation of ConfuserEx protected applications, without the worry of expiring or paywalled file downloads. 

## How to use?
This is the recommended order of tools, but other tools are available at your disposal. 
1. Download files via `git clone` or through the latest release.
2. Run `UnconfuserEx.exe` - This unpacks the application.
3. Run `ConfuserEx Proxy Call Fixer v2.exe` - Fixes proxy function calls.
4. Run `ConfuseExConstantDecryptor.exe` - Fixes strings.
5. Run `ConfuseExSwitchKiller.exe` (might crash) - Fixes switch control flow.
7. (optional) Run `ConfuserExFixer.exe` - Fixes general errors
8. Clean up with [de4dot](https://github.com/de4dot/de4dot)
9. Open the executable in [dnSpy](https://github.com/dnSpy/dnSpy), [Ghidra](https://github.com/NationalSecurityAgency/ghidra), etc.

## Sources
* https://youtu.be/X0F_-sE-6GU
* https://github.com/CodeShark-Dev/NoFuserEx
* https://www.youtube.com/watch?v=pgNr4YzgP9I

## Other possibly helpful tools
Here are some other tools that might be helpful. They could also entirely replace the tools in this list. I need to test more with them.
* https://github.com/ViRb3/de4dot-cex
* https://github.com/BedTheGod/ConfuserEx-Unpacker-Mod-by-Bed/tree/1.1

## Tools contained:
* UnconfuserEx - Unpacks ConfuserEx protected applications
* NoFuserEx - Removes anti-tamper, anti-debugger, anti-dump, fixes proxy calls and constants
* ConfuserEx ProxyCallFixer v2 - Fixes proxy function calls
* ConfuserExConstantDecryptor.exe - Fixes strings/constants
* ConfuserExceptionsRestore.exe - Fixes any errors
* ConfuserExCfgKiller.exe - Fixes any errors
* ConfuserExCallFixer.exe - Same as ProxyCallFixer
* ConfuserExDupPopPatcher.exe - 
* ConfuserExExpressionKiller.exe - Fixes control flow (Doesn't work on newer versions)
* ConfuserExFixer.exe - Fixes errors
* ConfuserExMethodsDecryptor.exe - 
* ConfuseExSwitchKiller.exe - Fixes switch control flow

