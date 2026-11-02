# swe-delta

AI 时代软件工程整条链路上的做法：需求怎样孵化、知识怎样维护，以及编码、测试、上线、观测。只写关键环节和措施，不写具体实现。

三角洲是上游的东西沉积下来的地方，Δ 是变更。需求在上游孵化，确认后记成对现状的变更，上线后沉成事实。

## 文档

两篇正交，合在一起用。每个知识单元同时落在一个成熟度层和一个结构层上。

| 文件 | 解决的问题 |
|---|---|
| [knowledge-maturity-and-incubation.md](knowledge-maturity-and-incubation.md) | **状态**。知识按确定性分成事实层、承诺层、孵化层。需求从信号孵化，经门禁沉到线上。 |
| [ddd-structure-and-incremental-change.md](ddd-structure-and-incremental-change.md) | **结构**。知识按领域组织成 L0 语言、L1 领域、L2 映射、L3 实现。一次变更之后，知识库仍然自洽。 |
