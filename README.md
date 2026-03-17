# Visual Release Proof

此仓库仅用于公开“发布者身份证明”材料，不包含私有源码。

## 发布者公钥指纹

`7A7F3D5D77C4039B860AFA10186770307005E4DC`

## 最新版本

- `v3.8.0`

## 已发布版本

- `v3.8.0`: `releases/v3.8.0/`
- `v3.7.0`: `releases/v3.7.0/`
- `v3.6.1`: `releases/v3.6.1/`

## 第三方验证

1. 下载目标版本目录中的公钥（示例：`releases/v3.7.0/public-key.asc`）
2. 执行：
   - `gpg --import public-key.asc`
   - `git verify-tag vX.Y.Z`
   - `git show vX.Y.Z --show-signature`
3. 核对签名指纹与本仓库公布值一致
