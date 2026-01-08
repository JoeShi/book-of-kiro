---
title: "常见问题"
weight: 52
bookToc: true
---

# Kiro 企业版常见问题

## 用户管理

### **企业用户如何查询员工使用情况**

Kiro 提供以下方式查看使用情况：

- Kiro usage dashboard。在 Kiro 企业管理控制台中，在设置界面启用 Kiro usage dashboard，然后在企业管理控制台的 Dashboard 界面可以查看
- Kiro user activity report。在 Kiro 企业管理控制台中，在设置界面启用 Kiro user activity report，数据会以 CSV 格式保存到 Amazon S3 上。如果您在配置过程中遇到了问题，通常是需要设置 Amazon S3 的权限，请参考[此文档](https://kiro.dev/docs/enterprise/monitor-and-track/user-activity/#prerequisite)。

### **如何使用 API 实现订阅或批量订阅？**

目前 Kiro 并没有公开 API/SDK ，但是有社区方案通过手动构造 SigV4 签名的方式实现了批量订阅（或基于 API 自动订阅），详见此 [GitHub Repo](https://github.com/DiscreteTom/kiro-management-api).
