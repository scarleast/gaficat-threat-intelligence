## 写在前面

“你最近有关注到什么有意思的漏洞吗？”

这是一次面试中面的问题，虽然从事威胁捕获、漏洞管理、安全运营相关工作5年多时间，但是这个问题一度让我语塞。漏洞是一个很有意思的话题，以漏洞为出发点可以延展出非常多的内容：漏洞本身、PoC/EXP、在野漏洞利用、漏扫规则、HIDS规则、NIDS规则、样本、IoC等等。我曾经花费了大量的时间在给这些内容建立关联，建立运营机制上，因为这些内容碎片化严重：各大机构公开的结构化信息，博客、论坛、twitter、公众号的社区情报，git仓库、RSS、蜜罐等安全产品清洗后的情报等等。但反思一下，从业五年，无论做了多少事，我工作的价值其实就是回答：”最近有什么新漏洞吗？“

市面上有非常多优秀的团队在威胁情报、漏洞库方面做的很棒，比如微步、阿里云漏洞库、安恒安全星图等等。作为个人，无论财力还是精力上都无法与这些优秀团队比拟，但作为热爱这个行业的从业者，还是希望贡献自己的绵薄之力。

这个仓库一方面将以周报的形式发布一些个人认为重要的漏洞情报（漏洞情报不是越多越好，对于大多数人而言，有PoC/EXP，有在野漏洞利用的情报才有用）。另一方面，也会将自己工作中遇到的需求，转化成相应服务。

## 更新计划

- 周报
  - 漏洞情报
    - [ ] CISA：1. 有CVE编号。2. 有可靠的证据表明，漏洞在野外被积极利用。3. 有明确补救措施，例如供应商提供的更新。
    - [ ] 蜜罐情报： 有可靠的证据表明，漏洞在野外被利用。
    - [ ] ExploitDB：漏洞利用数据。
    - [ ] 社区情报：1. 高危。2. 有分析文章、PoC/EXP。
  - 漏扫情报（开源漏扫规则能够转化成其他流量类产品规则）
    - [ ] nuclei
    - [ ] afrog
- 服务
  - [ ] url/流量特征反查：根据URL、流量特征反查漏洞编号。