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

# TRẦN THÀNH DANH Save Instance

Hay gọi tắt là USSI, một dự án nhằm hồi sinh chức năng saveinstance của Synapse X.<br />
Lý do: Nhiều Executor hiện tại hoạt động rất tệ khi liên quan đến việc lưu lại Instance của game để chỉnh sửa.

