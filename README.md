# mannix-proxy-rules

个人分流规则集，供 Surge / Clash 通过 RULE-SET 引用。

- `direct.list`：直连规则，一行一条，格式 `DOMAIN,xxx` / `DOMAIN-SUFFIX,xxx`，不写策略，策略由订阅模板中引用它的那一行决定。
- 仅放可公开内容，不要写 IP、内网段、账号或密钥。
