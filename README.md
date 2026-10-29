# AI4Science 虚拟筛选库

独立的 GitHub Pages 操作工作台。以 POISK v1.1 的原始结合记录为单位，默认展示全部抗体记录；纳米抗体（来源标注 VHH）作为其中一个筛选类别。

- 关键词 / 抗体类型 / 提取审核 / 序列字段条件筛选
- 分页表格、逐记录详情、全部 47 个原始字段
- 重轻链及靶点序列、亲和力原文、实验条件、表位和审核证据
- 浏览器本地候选清单；导出完整 JSON 或标准氨基酸链 FASTA
- 不实施对接、结构预测、亲和力预测或虚构综合评分

## 来源与许可
Tupikina, D., Roncoli, A., Bujotzek, A., & Abanades, B. (2026). POISK: Patent-extracted Organization of Immunoglobulin Sequence Knowledge (Version 1.1). Zenodo. https://doi.org/10.5281/zenodo.21775623

数据许可：CC BY 4.0 https://creativecommons.org/licenses/by/4.0/

原始 CSV MD5：f0c1f098abf1756e4b9891aa4dc028ee。本站将 CSV 重排为检索索引与分块 JSON，完整记录保留原字段与原文。数据包含 93,193 条记录，一条抗体可能对应多条记录。下载与转换日期：2026-10-29。

来源类型 VHH 不重新分类；无 VL 不等于 VHH。CONFIRMED 等是专利文本审核，不是独立实验验证。未将 v1.0.1 的折叠指标混入 v1.1。亲和力保留原始单位与描述，不进行跨方法数值排序。原始专利须用于关键字段核查。

本地预览：python3 -m http.server 8767
