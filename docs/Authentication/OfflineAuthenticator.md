# 离线验证器
用于离线登录的验证器，只需填写玩家名即可进行验证

## 构造函数
```csharp
public OfflineAuthentication(string username)
{
    Username = username;
}
```
| 参数 | 类型 | 描述 |
|:----------|:-----------|:-----------------------------|
| username | string | 用于启动的用户名（玩家名） |

除了上方的函数，在后面还需要添加 `.OfflineAuth()` 来匹配BaseAccount。
例如：
``` csharp
var account = new OfflineAuthentication(username).OfflineAuth();
```
