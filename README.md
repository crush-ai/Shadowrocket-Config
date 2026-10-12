# Shadowrocket-Config

Shadowrocket 融合配置文件。

- 来源 1：[johnshall 懒人配置（含策略组）](https://johnshall.github.io/Shadowrocket-ADBlock-Rules-Forever/lazy_group.conf)
- 来源 2：[LingJingMaster 可分享版](https://raw.githubusercontent.com/LingJingMaster/Shadowrocket-Rules/refs/heads/main/Shadowrocket.conf)
- 融合日期：2026-10-12

## 使用方法

在 Shadowrocket 中通过 URL 导入：

```
https://raw.githubusercontent.com/crush-ai/Shadowrocket-Config/main/Shadowrocket-merged.conf
```

## 融合说明

- 以来源 1 为基础，保留其完整的中文注释、DNS 设置与策略组体系
- 合并来源 2 独有的策略组（DNS 防泄露、邮件服务、代码托管、汇丰香港、香港银行、券商服务、私有网络、国内服务、苹果推送、非中国、漏网之鱼、其他节点）
- 合并来源 2 独有的 35 条规则（微信/豆包/DeepSeek 直连、邮件、GitLab/Atlassian、香港银行与券商、Apple 推送等），重复的规则集已去重
- 来源 2 的 emoji 策略组名已映射为来源 1 的组名体系
