# TRẦN THÀNH DANH Save Instance
# Trần Thành Danh

```lua
local Params = {
 RepoURL = "https://github.com/tranthanh-vn/TranDanh/tree/main",
 SSI = "saveinstance",
}
local synsaveinstance = loadstring(game:HttpGet(Params.RepoURL .. Params.SSI .. ".luau", true), Params.SSI)()
local Options = {}
synsaveinstance(Options)
```
