# CAUD_Pipeline

针对合同长文本，美国律协以及斯坦福大学开源了英文合同通用要素抽取，涵盖以下四十一类抽取内容，输入为合同全文，输出为合同内对应的内容，该四十一类通用抽取内容基本上涵盖了所有英文合同内需要关注的风险点，为所有业务部门的英文合同通用：

1. 协议名 - Document Name
2. 缔约主体 - Parties
3. 缔约时间 - Agreement Date
4. 协议生效日期 - Effective Date
5. 协议失效日期 - Expiration Date
6. 续约条款 - Renewal Term
7. 通知终止续约 - Notice Terminate Renewal
8. 管辖权 - Governing Law
9. 最惠国待遇 - Most Favored Nation
10. 非竞争条款 - Non-Compete
11. 独家经营权 - Exclusivity
12. 禁止挖角客户 - No-Solicit of Customers
13. 竞争限制例外 - Competitive Restriction Exception
14. 禁止挖角员工 - No-Solicit of Employees
15. 非贬低条款 - Non-Disparagement
16. 便利终止 - Termination of Convenience
17. 优先购买权/优先转让权/优先谈判权 - ROFR/ROFO/ROFN
18. 控制权变更 - Change of Control
19. 反转让条款 - Anti-Assignment
20. 收益/利润分成 - Revenue/Profit Sharing
21. 价格限制 - Price Restriction
22. 最低承诺 - Minimum Commitment
23. 数量限制 - Volume Restriction
24. 知识产权所有权转让 - IP Ownership Assignment
25. 共同知识产权所有权 - Joint IP Ownership
26. 许可授权 - License Grant
27. 不可转让许可 - Non-Transferable License
28. 联营知识产权许可方 - Affiliate IP LicenseLicensor
29. 联营知识产权许可受许方 - Affiliate IP LicenseLicensee
30. 无限制/无限制使用许可 - Unlimited/All-You-Can-Eat License
31. 不可撤销或永久许可 - Irrevocable or Perpetual License
32. 源代码抵押 - Source Code Escrow
33. 终止后服务 - Post-Termination Services
34. 审计权 - Audit Rights
35. 无上限责任 - Uncapped Liability
36. 有上限责任 - Cap on Liability
37. 约定违约金 - Liquidated Damages
38. 质保期限 - Warranty Duration
39. 保险 - Insurance
40. 不起诉条款 - Covenant Not to Sue
41. 第三方受益人 - Third Party Beneficiary

请注意，美国律协发动White & Case、Cooley、Orrick等律所，由资深律师给定标注范围、给出标注指南，发动斯坦福大学法学院、加州大学法伯克利分校法学院在校学生参与标注，共计标注510份文档，涵盖41项抽取信息，合计标注1万3000余条数据。

如果事务所想要做中文合同要素抽取，需要由业务部门律师给定标注框架、发动实习生进行标注。

Inspired by:

1. https://www.atticusprojectai.org/
2. https://zhuanlan.zhihu.com/p/371351793
3. https://zhuanlan.zhihu.com/p/371353549
