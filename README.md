# Visual Release Proof

此仓库仅用于公开“发布者身份证明”材料，不包含私有源码。

## 发布者公钥指纹

`7A7F3D5D77C4039B860AFA10186770307005E4DC`

## 已发布版本

- v3.6.1: `releases/v3.6.1/`

## 第三方验证

1. 下载 `releases/v3.6.1/public-key.asc`
2. 执行：
   - `gpg --import public-key.asc`
   - `git verify-tag v3.6.1`
   - `git show v3.6.1 --show-signature`
3. 核对签名指纹与本仓库公布值一致
