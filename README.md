# Trần Thành Danh

```lua
local Params = {
 RepoURL = "https://github.com/tranthanh-vn/TranDanh/tree/main",
 SSI = "saveinstance",
}
local synsaveinstance = loadstring(game:HttpGet(Params.RepoURL .. Params.SSI .. ".luau", true), Params.SSI)()
local Options = {} -- Documentation here https://luau.github.io/UniversalSynSaveInstance/api/SynSaveInstance
synsaveinstance(Options)
```

# Universal Syn Save Instance

Or shortly USSI, a project aimed at resurrecting saveinstance function from Synapse X.<br />
Reason: Many Executors fail miserably at providing good user experience when it comes to tinkering with saving instances.

> [!WARNING]
> As stated under the Section 7 (b) in the LICENSE:
> - You **MUST** always include the following Credit string: `UniversalSynSaveInstance https://discord.gg/wx4ThpAsmw`
> - You are **NOT** allowed to claim authorship of the source code provided in this repository
> - You **MUST** always include the following [License](https://github.com/luau/UniversalSynSaveInstance/blob/main/LICENSE)

> [!TIP]
> Important part about this saveinstance is that it doesn't modify anything, therefore reduces the amount of detection vectors by a lot.<br />
> You can also enable the `SafeMode` option to completely bypass any detections and save **ANY** game!<br /><br />
> If this script is helpful to you, please click `⭐ Star` in the upper right corner of the page to support it, thank you!


# 💖 Support Us & Our Work

> https://www.facebook.com/trnthdanh/
