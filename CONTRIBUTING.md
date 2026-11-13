# 贡献指南（Contributing）

欢迎补充有实锤来源的风险品牌条目。本项目只收录**可追溯**的记录，不做情绪化站队。

## 收录标准（必须同时满足）

1. **有可追溯来源**：行政处罚文书、央视 / 3·15 晚会、主流媒体调查报道、法院判决之一。每条在对应文件文末"资料来源"节附 URL。
2. **能落到法人主体**：品牌名（消费者可见）与企业 / 代工厂（法人主体）分开写，不能只写一个笼统名字。
3. **写清时间、地点、结果**：年份、城市、处罚金额 / 判决结果 / 整改情况；只写结论，不写过程，不写"据说""听说"。

## 不收录

- 无主体的小作坊、投诉平台单方爆料：单列为 B 档，注明"未见处罚结论"，不夸大为定性。
- 纯主观好恶、无证据的口碑评价。
- 未核实的传言、聊天截图、短视频道听途说。
- 已被收购 / 运营的品牌（属认知校准，不是抵制对象，归 `acquired-foreign-brands.md`）。

## 格式约定

表格第一列永远是**品牌名**，第二列**企业 / 涉事方**，第三列**问题 / 事实**。

- 品牌与企业分两列，不要混在一格。
- 同一品牌跨多个类别：主类别详写，其他类别只给一行跳转。
- 新增条目直接往对应分类文件表格里追加，不新建散落文件。

## 提交方式

1. Fork 本仓库，新建分支。
2. 往对应 `Spec/<品类目录>/xxx.md` 表格追加条目，文末补来源 URL。
3. 提交信息写明：`补充 <分类>：<品牌名>（<一句话问题>）`。
4. 提 Pull Request 说明证据来源链接。

## 分类对照

| 你要补充的内容 | 放到哪个文件 |
| ---- | ---- |
| 用工 / 户籍 / 年龄 / 院校歧视、价值观冲突 | `Spec/08-boycott/boycott-discrimination.md` |
| 已被司法定性的传销 | `Spec/08-boycott/pyramid-scheme.md` |
| 辱华、分裂国家、抵制新疆棉、侮辱领袖、区别对待 | `Spec/08-boycott/china-boycott.md` |
| 食安抽检、异物、召回、处罚 | `Spec/01-food/food-safety.md` |
| 添加剂标准差异、非法添加物 | `Spec/01-food/additive-gap.md` |
| 问题儿童读物 / 教材 | `Spec/06-kids/toxic-textbooks.md` |
| 央视 3·15 晚会曝光 | `Spec/09-reference/315-exposed.md` |
| 贴牌 / 卖吊牌 | `Spec/05-daily-use/oem-licensed.md` |
| 山寨碰瓷、假老字号鉴别 | `Spec/01-food/shanzhai-food.md` |
| 被中资收购 / 运营（认知校准） | `Spec/09-reference/acquired-foreign-brands.md` |
| 塌房艺人 / 代言风险 | `Spec/08-boycott/toxic-celebrities.md` |
| 快时尚 / 服装质量 | `Spec/02-clothing/fashion-quality.md` |
| 装修 / 家居 | `Spec/03-living/home-renovation.md` |
| 出行 / 交通 | `Spec/04-travel/travel-pitfalls.md` |
| 奶制品选购 | `Spec/01-food/dairy-guide.md` |
| 日常小物件（洗护 / 卫生巾 / 数码配件 / 小家电 / 厨房用品） | `Spec/05-daily-use/daily-items.md` |
| 预付跑路 / 会销坑老 | `Spec/07-services/prepaid-scams.md` |
| 儿童玩具 / 童装 / 文具作业本 | `Spec/06-kids/kids-products.md` |
