# 发布者身份证明（公开材料）

- 项目：Visual
- 版本 Tag：`v3.8.0`
- 提交 SHA：`662d9edb7245c4de5d849d4ed865fd2fad4ca423`
- 提交作者：`JiangnanZhang-2006 <zjn.2006@foxmail.com>`
- 提交时间：`2026-03-17T23:00:16+08:00`
- 生成时间（UTC）：`2026-03-17T15:07:28Z`

## 第三方验证步骤

1. 导入公钥（若提供）：
   ```bash
   gpg --import public-key.asc
   ```
2. 验证 Tag 签名：
   ```bash
   git verify-tag v3.8.0
   git show v3.8.0 --show-signature
   ```
3. 核对签名身份与指纹是否一致：
   - 指纹见 `gpg-fingerprint.txt`
   - 签名详情见 `tag-signature.txt`

## 公开文件清单

- `PUBLIC_RELEASE_PROOF.md`：面向外部的验证说明
- `tag-signature.txt`：Tag 与签名详情输出
- `tag-verify.txt`：`git verify-tag` 输出
- `gpg-fingerprint.txt`：公钥指纹信息（若可导出）
- `public-key.asc`：发布公钥（若可导出）
