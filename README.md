# HZAU_Zotero 使用须知

- 制作人：小汪
- 邮箱：zhewang0124@gmail.com
- 最近更新：2026/03/20

本项目提供适配华中农业大学最新毕业论文规范的 Zotero 引文样式（CSL）。
针对自然科学类和人文社科类的不同规范要求，本次更新正式拆分为两套样式文件：

1. `hzau-thesis-author-date-natural-sciences.csl`：适用于自然科学类的“著者-出版年”制引文格式。
2. `hzau-thesis-author-date-social-sciences.csl`：适用于人文社科类的“著者-出版年”制引文格式。

## 使用说明

请重点参考最新长文教程：
[《华中农大毕业论文 Zotero 引文样式更新：两套 CSL、上手方法与使用说明》](https://mp.weixin.qq.com/s/hmVjrI4cRX3e33ZTbroYDQ)

过往基础参考资料：

1. [《基于Zotero的毕业论文参考文献工作流》](https://mp.weixin.qq.com/s/4lZkyntmUcvByCOkAU5k6g)
2. [《基于Zotero的适用于华农毕业论文的reference格式》](https://mp.weixin.qq.com/s/X2IHkiTreDr4FS0iH0-BMQ)

### 安装方法

前提是使用 Zotero 管理文献：
下载好对应的 `.csl` 文件以后，双击即可导入到 Zotero 里；或在 Zotero 中“编辑 -> 设置 -> 引用 -> 样式 -> 添加样式（+）”手动导入。

### 注意事项

引用的最终效果很大程度上取决于原始文献的 metadata（点击文献后右边窗格的 Info）。如果你发现生成的参考文献格式不对，通常需要检查元数据：

- **Language（语言）**：如果你需要中英混排，一定要在 Zotero 里将对应文献条目的语言设定准确（英文为 `en`，中文为留空或使用 `zh-CN`）。
- **Journal Abbr.（刊名简称）**：推荐外文期刊补全期刊缩写，以符合外文缩写不加缩点的要求。
- **缺失数据**：注意补全诸如“地点”、“页码”、“卷次”等信息以避免不完整。

> ⚠️ **重要提示**：CSL 目前无法稳定实现中文参考文献按拼音排序，**最终提交论文前，请务必人工检查中文参考文献的排序。**

<img width="351" alt="image" src="https://github.com/WangWaud/HZAU_Zotero/assets/82741778/acd8b36d-f957-4787-9a4a-6fe37284a32d">

**最后，祝毕业顺利，前途似锦！**

（如果能前往推文赞赏一杯咖啡那就更好了！）

更新日志：

- 2026/03/20 适配最新规范，拆分为“自然科学类”和“人文社科类”两套独立 CSL，并修正大量文内引注及参考文献细节
- 2022/05/24 期刊斜体已添加
