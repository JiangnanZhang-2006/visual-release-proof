# Visual Release Proof

此仓库仅用于公开“发布者身份证明”材料，不包含私有源码。

## 发布者公钥指纹

`7A7F3D5D77C4039B860AFA10186770307005E4DC`

## 最新版本

- `v4.0.0`

## 已发布版本

- `v4.0.0`: `releases/v4.0.0/`
- `v3.8.0`: `releases/v3.8.0/`
- `v3.7.0`: `releases/v3.7.0/`
- `v3.6.1`: `releases/v3.6.1/`

## 交付包信息

- 私有源码交付包：`visual-v4.0.0.zip`
- SHA256：`d8d5e33565ae49997295746dffb3bca19a6141762bb90dba8174e60b93955153`
- 本仓库仅公开签名证明材料，不托管源码压缩包

## 第三方验证

1. 下载目标版本目录中的公钥（示例：`releases/v3.7.0/public-key.asc`）
2. 执行：
   - `gpg --import public-key.asc`
   - `git verify-tag vX.Y.Z`
   - `git show vX.Y.Z --show-signature`
3. 核对签名指纹与本仓库公布值一致
