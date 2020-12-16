# CMSTP

Based on:

1. https://oddvar.moe/2017/08/15/research-on-cmstp-exe/
2. https://0x00-0x00.github.io/research/2018/10/31/How-to-bypass-UAC-in-newer-Windows-versions.html

This is a more consistent implementation that the one provided by `0x00-0x00` and is completely in .NET; no need for PowerShell.

Note: This was not tested with staged payloads, it was only tested with on-disk payloads.

## Usage

```
execute-assembly /tmp/CMSTPBypass.exe c:\windows\tasks\beacon.exe
```



