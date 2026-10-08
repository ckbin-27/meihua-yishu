---
name: meihua-yishu
description: |
  梅花易数（邵雍一脉）起卦断卦方法论的总入口。当用户要"用时间/数字/所见之物/声音/字画起卦"、
  要"读懂本卦互卦变卦的体用"、要"按五行生克比和断吉凶"、要"定应期/看外应（三要十应）"、
  或要"查八卦万物类象、做射覆观物、用坐端加数"时激活。
  不适用于：纯信息查询、医学/法律/财务等专业判断、以及"无故不占"的妄测。
  关键触发词：梅花易数、起卦、先天起卦、后天端法、体用、互卦、变卦、五行生克、比和、
  应期、克应、三要十应、外应、八卦类象、射覆、坐端、加数、不動不占、理在数先。
metadata:
  cangjie.generated-by: cangjie-tools v2.5.0
  cangjie.variant: single
  cangjie.bundle-id: bundle.meihua-yishu
  cangjie.capability-count: 11
  cangjie.entrypoint-count: 1
---
# 梅花易数 — 全书能力入口

## 触发与不触发

**适用**：与本书能力域相关的咨询与任务（见下方路由表的意图列）。
**不适用**：
- 不以卦名直断吉凶（须以体用生克为据）
- 不用于无'动/怪/异/问'之兆的妄测（不動不占，不因事不占）
- 不替代医学、法律、财务等专业判断
- 不用于纯信息查询类问题

## 核心原则（常驻速览，概览类问题读到这里即可回答）

1. 起卦两途：先天（数→卦，年月日时/物数/声音/字画）与后天（物象+方位端法），皆以乾1兑2离3震4巽5坎6艮7坤8定卦、除六取动爻。
2. 成卦分体用：无动爻为体（主/我），有动爻为用（事）；互卦为中应、变卦为末应。
3. 五行生克比和断吉凶：用生体/比和/体克用吉，用克体凶，体生用为泄气非利；体党多则盛、用党多则衰。
4. 体宜乘旺、克体宜衰；坐行卧立定应期迟速，生体之日为吉期、克体之日为凶期。
5. 须参外应（三要十应）与《易》辞，并以'理'校数——不動不占、理在数先、不可死执一法。

## 能力路由（先读本表，按意图加载 1 张能力卡）

| 用户意图 | 先读 | 补读/备注 |
|---|---|---|
| 用年月日时/数字/物数/声音/字数起卦；先天起卦法怎么算；卦以八除、爻以六除 | references/capabilities/qigua-xiantian.md | references/capabilities/qigua-houtian.md、references/capabilities/ti-yong-fen.md |
| 见物/人/声/色怎么起卦（端法）；后天起卦、方位起卦、为人占；字占怎么算 | references/capabilities/qigua-houtian.md | references/capabilities/qigua-xiantian.md、references/capabilities/ti-yong-fen.md、references/capabilities/bagua-leixiang.md |
| 怎么分体用、哪个是体哪个是用；互卦/变卦什么意思、本互变怎么读；动爻分体用 | references/capabilities/ti-yong-fen.md | references/capabilities/wuxing-shengke.md |
| 体用生克怎么断吉凶；用克体凶吗、比和吉吗、体生用为什么不好；体党用党、真生真克轻重 | references/capabilities/wuxing-shengke.md | references/capabilities/guaqi-yingqi.md、references/capabilities/shiba-zhan.md、references/capabilities/san-yao-shi-ying.md |
| 应期怎么算、什么时候应验；卦气旺衰、体旺体衰；坐行卧立定迟速 | references/capabilities/guaqi-yingqi.md | references/capabilities/wuxing-shengke.md |
| 占婚姻/求财/失物/疾病/出行/行人/官讼怎么断；梅花易数十八占、失物变卦方位、疾病医药取象 | references/capabilities/shiba-zhan.md | references/capabilities/bagua-leixiang.md、references/capabilities/wuxing-shengke.md |
| 外应怎么用、三要十应；占时听到的/看到的算不算兆；内卦和外应矛盾信哪个 | references/capabilities/san-yao-shi-ying.md | references/capabilities/lilun-biantong.md、references/capabilities/wuxing-shengke.md |
| 乾/坤/震/巽/坎/离/艮/兑代表什么；八卦万物类属、某卦对应什么人/物/身体/方位 | references/capabilities/bagua-leixiang.md | references/capabilities/qigua-houtian.md、references/capabilities/shiba-zhan.md |
| 射覆怎么断、猜物、笼中物/手中物占；观物戏验、变爻为主 | references/capabilities/she-fu-guanwu.md | references/capabilities/ti-yong-fen.md、references/capabilities/bagua-leixiang.md、references/capabilities/lilun-biantong.md |
| 卦象和常理矛盾怎么办、为什么同一卦结论不同；理在数先、心易、变通、不動不占 | references/capabilities/lilun-biantong.md | references/capabilities/san-yao-shi-ying.md |
| 同一时间起卦怎么区分、同卦怎么断；加姓氏画数、坐端诀、以坐为中定八方 | references/capabilities/zuoduan-jia-shu.md | references/capabilities/qigua-xiantian.md、references/capabilities/san-yao-shi-ying.md |

**非能力类查询**：
- 书名/作者/章节/整书概览 → references/overview.md
- 术语解释 → references/glossary.md
- 决策规则速查（不需要原文依据时） → references/cheatsheet.md
- 完整意图与关键词索引（本表未覆盖的意图先查这里） → references/capability-index.md

## 加载规则

- 每次任务先读本文件，再按路由表加载 **1** 张能力卡；任务明确跨域时最多加载 2 张。
- 概览/书名类问题不加载能力卡，用「核心原则」与 overview.md 回答。
- 路由表与 capability-index.md 都无法命中的意图，明确告知超出本书范围，不要硬套。

## 边界与判停

- 已给出'起卦→体用→生克→应期→外应'完整推断即止，不重复叠加信号
- 用户所问超出梅花体系（如具体医学诊断）时明确告知不适用
- 内卦与外应矛盾且无理可校时，明确说明不确定性
