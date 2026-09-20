# 0918_explore/supporters：根基结构的外部支撑

## 0. 用途与来源约定

本文件为 `answer.md` 中的根基结构提供外部支撑。`answer.md` 只含定义与严密推导；这里接入公认哲学观点与可核验的科学事实，并逐项标注来源层级。

来源层级约定：

- `canonical`：哲学与科学经典文本，按作者—著作—卷章引用；不伪造开放链接。
- `established`：已被广泛接受的学界观点或共识性结论。
- `empirical`：可核验的经验研究，附来源链接。
- `disputed`：仍存在重要争议的观点，标注争议位置。

各节末尾附来源清单；正文中的关键外部命题附 markdown 链接。本文件不改写 `answer.md` 的结构，只为其形式对象提供论据接口。

---

## 1. 结构—支撑对照表

| answer.md 对象 | supporters 支撑节 | 核心外部支撑 |
|---|---|---|
| \(\succeq_a\)、\(U_a\)、\(V_a\) | S2 | 期望效用表示定理；前景理论；偏好显示理论 |
| 价值维度与价值观来源 | S3 | Schwartz 基本价值观；Inglehart 后物质主义；SDT |
| \(\Gamma_a\) 目的选择器 | S4 | 亚里士多德目的论与慎思；意向—行动差距研究 |
| \(\Pi_a\) 态度—行动规则 | S5 | 控制论反馈；具身认知；认知失调与行为反馈 |
| \(N_a\)、规范过滤器 | S6 | 休谟实然—应然；康德假言/定言命令；反思平衡 |
| \(C_a\) 主体归属与承诺 | S7 | Frankfurt 二阶意愿；Sartre 自欺；自决理论 |
| \(M_a\) 意义解释回路 | S8 | Steger 意义三成分；Ricoeur 叙事同一性；Taylor 强评价 |
| \(E\)、AI 内生扰动 | S9 | 延伸心智；LLM 说服研究；LLM 语义争论 |
| 自然生命、有限性接口 | S10 | TMT；海德格尔向死而在；Frankl 意义疗法 |

---

## S2. 偏好关系与效用表示

### S2.1 效用作为偏好的表示，而非独立实体

`answer.md` 将价值层建立在偏好关系 \(\succeq_a\) 上，把 \(U_a:\mathcal F\to\mathbb R\) 视为满足条件时的数值表示。这一构造直接承接决策理论中的**期望效用表示定理**：当偏好满足完备性、传递性、连续性和独立性等公理时，存在效用函数使偏好序与实数大小一致（[von Neumann & Morgenstern](https://markus.scholar.princeton.edu/sites/g/files/toruqf2651/files/markus/files/fin_501_lecture_notes_2014.pdf) `canonical`；表示定理的现代表述见 [这里](https://www.sciencedirect.com/science/article/abs/pii/S0304406811000486?via%3Dihub=) `established`）。

这支撑了 `algorithm.md` 的一个关键约定：实数值只承载序关系，任何严格递增变换都不改变价值结构。效用函数的基数刻度不是“价值的客观量”。

### S2.2 实值表示只是有条件的近似

**前景理论**的经验证据显示，人类在风险、损失和概率权重上系统偏离期望效用模型；框架效应会改变选择（[Tversky & Kahneman 1981](https://era.ed.ac.uk/bitstream/handle/1842/25831/Kamwendo2017.pdf) `canonical/empirical`）。这说明 \(U_a\) 的表示条件在真实主体上经常不成立，价值函数应被理解为一种**建模选择**，而不是主体内部的真实刻度。支撑 `answer.md` 对“价值函数只是有条件表示”的表述。

### S2.3 从行为到偏好的反推是弱反推

**显示偏好理论**指出，从选择数据恢复偏好需要一致性条件（如 WARP、GARP），且多种偏好系统可以生成同样的可观测选择（[Journal of Economic Perspectives 综述](https://ftp.aeaweb.org/articles/pdf/doi/10.1257/jep.4.2.141) `established`）。**Manski 的识别问题**进一步说明，许多结构参数在观测数据下不可识别（[zbMATH 文献记录](https://zbmath.org/pdf/06988838.pdf) `established`）。

这为 `answer.md` 的结构族 \(\mathfrak R_a(E,D_a)\) 提供直接科学基础：从生活资料到人生观的逆映射本质上保持多解。

### S2.4 来源清单（S2）

- von Neumann & Morgenstern, *Theory of Games and Economic Behavior*（1944）：期望效用公理化。`canonical`
- Tversky & Kahneman, “The Framing of Decisions and the Psychology of Choice,” *Science* 211（1981）。`canonical`
- Samuelson（1938）与 Afriat（1967）：显示偏好。`established`
- Manski, *Identification Problems in the Social Sciences*（1995）。`established`

---

## S3. 价值层的维度与来源

### S3.1 人类价值具有跨文化的结构

**Schwartz 基本价值观理论**区分十类动机型价值，并发现它们在多个文化中呈现稳定结构；2012 年修订版区分 19 个细分价值（[Schwartz 2012](https://pubmed.ncbi.nlm.nih.gov/22823292/) `empirical`；测量结构见 [PVQ-40 研究](https://pubmed.ncbi.nlm.nih.gov/22329443/)）。支撑 `answer.md` 的多元价值表示 \(V_a:S\to\mathbb R^k\)：价值不是单一实数，而是多维度结构。

**Inglehart 的物质主义—后物质主义**理论及世界价值观调查证据显示，价值观随代际和社会条件变化（[Springer 研究](https://link.springer.com/article/10.1007/s11205-026-03913-w) `empirical`）。支撑 \(N_a\)、\(\succeq_a\) 随生活历史 \(\mathcal H_a\) 更新的时间性。

### S3.2 基本心理需要与内在目标

**自我决定理论**提出自主、胜任、关系三种基本心理需要，其满足与幸福感正相关；内在目标（个人成长、亲密关系、社区贡献）相对外在目标（财富、名声、外貌）更稳定地支持幸福（[Ryan & Deci 2000](https://psycnet.apa.org/doiLanding?doi=10.1037%2F0003-066X.55.1.68&facet=app&mode=light) `canonical`；[SDT 与繁荣综述](https://academic.oup.com/edited-volume/28143/chapter-abstract/212907440) `established`；[毕业后的内在/外在目标后果](https://www.sciencedirect.com/science/article/abs/pii/S0092656608001360?via%3Dihub) `empirical`）。

这为 \(U_a\) 提供可检验的经验内容，同时提示：AI 若只拟合外显偏好，可能放大外在目标排序而低估基本需要的满足。

### S3.3 来源清单（S3）

- Schwartz, “An Overview of the Schwartz Theory of Basic Values,” *Online Readings in Psychology and Culture*（2012）。`established`
- Inglehart, *The Silent Revolution*（1977）。`established`
- Deci & Ryan, “The 'What' and 'Why' of Goal Pursuits,” *Psychological Inquiry*（2000）。`canonical`

---

## S4. 目的层 \(\Gamma_a\)

### S4.1 目的作为生活方向的古典来源

**亚里士多德**把幸福理解为灵魂合乎德性的活动，把目的理解为功能与卓越，并把慎思与明智（φρόνησις）作为从目的到行动的实践推理环节（*Nicomachean Ethics* I.7, VI；[Routledge 德性伦理词条](https://www.rep.routledge.com/articles/thematic/virtue-ethics/v-1/sections/aristotle-and-ancient-virtue-ethics) `established`）。支撑 \(\Gamma_a\) 的规范来源：目的选择包含“何种生活值得过”的实质判断，不能化约为即时偏好最大化。

### S4.2 意向与行动之间存在结构性间隙

实证心理学长期记录**意向—行动差距**（intention–behavior gap）：有意向不等于执行；执行意向与具体计划能提高执行率（[Gollwitzer & Bargh 自动性研究](https://www.socmot.uni-konstanz.de/sites/default/files/05_Gollwitzer_Bargh_Automaticity_Processes.pdf) `established`）。情感预测研究显示人对自己未来感受的预测存在系统性偏差（[情感预测综述](https://www.sciencedirect.com/science/chapter/bookseries/abs/pii/S0065260103010062) `established`）。

这支撑 `answer.md` 的两个分离：目的层与态度层之间的桥需要 \(\Pi_a\)；\(\Gamma_a\) 的产物不是承诺轨迹本身。

### S4.3 多目标与目标冲突

目标干扰与多目标并存会降低实现率（[多目标与执行成功研究](https://unbscholar.dspace.lib.unb.ca/server/api/core/bitstreams/f47d8e1e-fc38-40f7-82b6-e87c20b5fad9/content) `empirical`）。支撑 \(\Gamma_a\to 2^{\mathcal F}\) 返回目标集合而非单点：真实主体同时携带多个可能冲突的目的。

### S4.4 来源清单（S4）

- Aristotle, *Nicomachean Ethics*。`canonical`
- Gollwitzer, “Implementation Intentions,” *American Psychologist*（1999）。`established`
- Wilson & Gilbert, “Affective Forecasting,” *Advances in Experimental Social Psychology*（2003）。`established`

---

## S5. 态度层 \(\Pi_a\) 与控制论接口

### S5.1 反馈控制是态度的科学图像

**控制论**传统把有目的系统描述为“目标—感知—行动—反馈”的闭环（Wiener 1948；Rosenblueth, Wiener & Bigelow 1943）。\(\Pi_a:(h,b,g,n)\to\Delta(\mathcal A(h))\) 作为处境—行动算子，直接承接这一传统。`canonical`

### S5.2 身体与情感参与评价和决策

**躯体标记假说**认为，情绪与身体状态参与决策评估，前额叶损伤导致“知道但无法用感受加权”的决策障碍（[躯体标记假设综述](https://www.sciencedirect.com/science/article/abs/pii/S2352154617300736) `empirical`；[内感受觉察与决策的神经活动](https://www.sciencedirect.com/science/article/abs/pii/S0301051113001932) `empirical`）。**生成认知/自创生**传统主张认知系统通过自身组织与环境耦合产生意义（[Varela 传统综述](https://philarchive.org/archive/SALELD-2) `established`）。

这支撑 `answer.md` 的自然哲学接口：态度不是纯符号规则，其风险回应 \(\rho_a\)、冲突处理 \(\kappa_a\) 和修正机制 \(\chi_a\) 具有身体与情感基础。

### S5.3 行动反馈会重塑偏好

**认知失调**与**选择扩散效应**的证据显示，行动本身会改变事后偏好（[认知失调与执行功能研究](https://www.sciencedirect.com/science/article/abs/pii/S0010945221000769) `empirical`；[中国心理学综述](https://journal.psych.ac.cn/xlkxjz/CN/article/downloadArticleFile.do?attachType=PDF&id=49) `empirical`）。支撑 `answer.md` 的反馈回路：

\[
\Pi_a\xrightarrow{\mathcal T}\mathcal H_a^{t+1}\xrightarrow{\mathsf{Reflect}}\mathcal V_a^{\prime}.
\]

### S5.4 来源清单（S5）

- Wiener, *Cybernetics*（1948）。`canonical`
- Damasio, *Descartes' Error*（1994）。`canonical`
- Varela, Thompson & Rosch, *The Embodied Mind*（1991）。`established`
- Festinger, *A Theory of Cognitive Dissonance*（1957）。`canonical`

---

## S6. 规范层 \(N_a\) 与正当性

### S6.1 实然与应然的区分

**休谟**提出从“是”不能直接推出“应当”（*Treatise* III.i.1），**摩尔**进一步批评把“善”定义为自然性质（自然主义谬误）（[《对话》期刊的分析](https://www.cambridge.org/core/journals/dialogue-canadian-philosophical-review-revue-canadienne-de-philosophie/article/abs/isought-gap-the-factvalue-distinction-and-the-naturalistic-fallacy/50101AA1FBD5C51E9F2BE59D478224A9) `established`）。心理学内部也有同样的规范性警醒（[Facts, values, and the naturalistic fallacy in psychology](https://www.sciencedirect.com/science/article/abs/pii/S0732118X07000657) `established`）。

这支撑 `answer.md` 对 AI 的界限：算法拟合“人们通常如何选择”，不能由此推出“人应当如何选择”。

### S6.2 假言命令与定言命令

**康德**区分假言命令（服务于给定目的的手段规则）与定言命令（不依赖特定目的的普遍规范），并强调把人当作目的本身（[Groundwork 分析](https://unsworks.unsw.edu.au/bitstreams/fffa8dd4-5650-4aca-a9d6-f6dfab2e3fa2/download) `canonical`；[康德论善的表象](https://www.cambridge.org/core/journals/kantian-review/article/between-indubitably-certain-and-quite-detrimental-to-philosophy-kant-on-the-guise-of-the-good-thesis/5D0852DE2D769BD7DAA6F07C30507C89) `established`）。

这支撑 \(N_a\) 的两个层面：手段约束（可由算法计算）与原则约束（不能由给定目的推出）。AI 可以在给定 \(N_a\) 下优化，但 \(N_a\) 本身的正当来源需另设接口。

### S6.3 反思平衡作为正当化方法

**罗尔斯**的反思平衡描述主体在深思熟虑的判断与一般原则之间来回修正，以求得融贯的规范体系（[Stanford Encyclopedia 词条](https://plato.stanford.edu/entries/reflective-equilibrium/) `established`）。它支撑 \(N_a\) 的时间更新规则与 \(C_a\) 的“理由认可”维度：主体通过来回修正，而不是一次接受，形成自己的规范结构。

### S6.4 来源清单（S6）

- Hume, *A Treatise of Human Nature*（1739–40）。`canonical`
- Kant, *Groundwork of the Metaphysics of Morals*（1785）。`canonical`
- Rawls, *A Theory of Justice*（1971）§4, §9。`canonical`

---

## S7. 主体归属层 \(C_a\)

### S7.1 二阶意愿与认同

**Frankfurt** 区分一阶欲望与二阶意愿：一个人认同某个欲望，将其接纳为自己的意愿时，该欲望才在归属意义上属于他；由此形成人与自身关系的结构（[Frankfurt 层级理论综述](https://www.repository.cam.ac.uk/items/77f2e24f-b4fb-4ad4-a88d-637b224bbb9c) `established`；[Sartre 与 Frankfurt 的比较研究](https://onlinelibrary.wiley.com/doi/abs/10.1111/ejop.12882) `disputed`）。

这支撑 \(C_a\) 的“第一人称接受”维度：算法输出即使被采纳，也需要主体把它接纳入自己的意愿结构。Watson 等批评者指出层级理论有回归风险，提示 \(C_a\) 的判定不能只靠更高层意愿的递归（[Watson 批评的学位论文综述](https://discovery.ucl.ac.uk/id/eprint/10178104/1/Mphil%20thesis%20Laura%20Custers.pdf) `disputed`）。

### S7.2 自欺与认同的断裂

**Sartre** 认为主体可以把自己当作既定事实而逃避选择，即自欺（bad faith）（[Being and Nothingness 全文](https://archive.org/stream/in.ernet.dli.2015.69160/2015.69160.Jean-paul-Sartre-Being-And-Nothingness_djvu.txt) `canonical`）。支撑 \(C_a\) 的负面条件：一个人可以宣称某价值观属于自己而实际并不承担它；算法生成的人生观表述也可能成为这种自欺的素材。

### S7.3 自主需要真实的能力条件

**自我决定理论**的自主观要求行动被体验为自我认可的，而**关系性自主**传统强调，偏好形成过程中的操纵、支配性社会条件会削弱归属（[UCL 博士论文综述](https://discovery.ucl.ac.uk/id/eprint/10217153/2/Michael%20Thorne%20PhD%20Thesis%20for%20UCL%20Repository.pdf) `established`）。

这支撑 `answer.md` 对 AI 内生影响的警戒：若 AI 通过框架、情绪与权威感塑造偏好，即便事后得到认可，其偏好形成史也需要被纳入 \(C_a\) 的判定。

### S7.4 来源清单（S7）

- Frankfurt, “Freedom of the Will and the Concept of a Person,” *Journal of Philosophy* 68（1971）。`canonical`
- Sartre, *L'Être et le néant*（1943）。`canonical`
- Christman, “Autonomy and Personal History,” *Canadian Journal of Philosophy*（1991）。`established`

---

## S8. 意义层 \(M_a\) 与叙事接口

### S8.1 意义感的可操作三成分

心理学中意义感的“一致性—目的—重要性”三成分模型把意义操作化为生活可理解、有方向、值得投入（[Martela & Steger 2016](https://www.tandfonline.com/doi/full/10.1080/17439760.2015.1137623) `empirical`；[综述](https://www.sciencedirect.com/science/article/pii/S1469029224001365) `established`）。

这直接支撑 `answer.md` 对 \(M_a\) 的定位：可理解性、连续性、值得性和承诺理由。意义不是新的价值标尺，而是对结构的整合性评价。

### S8.2 强评价与身份

**Taylor** 认为自我认同依赖“强评价”：区分更高与更低、值得与不值得的定性框架（[牛津大学学位论文综述](https://ora.ox.ac.uk/objects/uuid:efc76649-6049-42b7-ae3c-5039c3b25bb5) `established`）。**Ricoeur** 提出叙事同一性：自我在情节化（emplotment）中把行动组织为时间中的身份（[情节化概念研究](https://era.ed.ac.uk/bitstream/handle/1842/20963/Afayori2016.pdf) `established`）。

这支撑 \(M_a=\mathsf{Interpret}(R_a,\mathcal H_a^{0:t})\)：意义解释把目的、态度、价值与生活历史组织为连续叙事。

### S8.3 关系与助人作为意义来源

经验研究表明，帮助他人与意义感正相关（[Greater Good 综述](https://greatergood.berkeley.edu/article/item/can_helping_others_help_you_find_meaning_in_life/success) `empirical`；[生活目的与社会联结的微观纵向研究](https://www.sciencedirect.com/science/article/pii/S0001691826007213) `empirical`）。**Buber** 的我—你关系传统把意义置于对话与相遇之中（[Buber 文集](https://archive.org/stream/writingsofmartin007421mbp/writingsofmartin007421mbp_djvu.txt) `canonical`）。

这支撑 \(N_a\) 中关系性规范与 \(\mathcal O\) 中他人维度的必要性：意义回路不是孤独主体的内部计算。

### S8.4 来源清单（S8）

- Martela & Steger, “The three meanings of meaning in life,” *J. Positive Psychology*（2016）。`empirical`
- Taylor, *Sources of the Self*（1989）。`canonical`
- Ricoeur, *Soi-même comme un autre*（1990）。`canonical`
- McAdams, “The Psychology of Life Stories,” *Review of General Psychology*（2001）。`established`

---

## S9. 环境模型、AI 内生扰动与语义界限

### S9.1 认知可以延伸进外部装置

**延伸心智论**主张，认知过程可以跨越颅骨与外部装置，只要该装置在认知回路中扮演与内部记忆同等的角色（[Clark & Chalmers 传统综述](https://philarchive.org/archive/ERKAPA.pdf) `established`）。这为 AI 作为“反思辅助器”提供哲学基础：AI 可以参与认知过程，而不因此自动成为主体。

### S9.2 AI 确实改变人的信念与观点

实证研究显示，LLM 生成的文本能够说服人改变政策立场，说服力接近人类写作（[Jakesch et al., *Nature Communications*](https://www.nature.com/articles/s41467-025-61345-5) `empirical`）；与人机共写会改变作者观点（[Co-Writing 研究](https://ar5iv.labs.arxiv.org/html/2302.00560) `empirical`）；聊天机器人可在政治说服中双向影响选民（[EurekAlert 报道](https://www.eurekalert.org/news-releases/1107627) `empirical`）。

这支撑 `answer.md` 的洞见：AI 是环境的内生扰动，其输出进入 \(\mathcal O,\mathcal A,\mathcal H\)，而不仅是外部观察器。

### S9.3 默认效应与选择架构

选择架构的**默认效应**能系统改变选择（[PNAS 政治捐赠研究](https://www.pnas.org/doi/abs/10.1073/pnas.2218385120) `empirical`；[默认效应元分析](https://journal.psych.ac.cn/xlkxjz/EN/Y2022/V30/I6/1230) `empirical`）。支撑对 AI 呈现方式的警戒：AI 对选项的排序、默认化和措辞本身构成对 \(\succeq_a\) 形成的干扰通道。

### S9.4 AI 的语义界限仍是争议焦点

**Searle 的中文屋**论证区分句法操作与语义理解（`canonical`）；**Dreyfus** 论证符号规则无法重建背景实践（[indiaai 综述](https://indiaai.gov.in/article/why-do-scientists-and-philosophers-agree-on-ai-hubert-dreyfus-s-views) `established`）；**Bender 等**提出 LLM 是“随机鹦鹉”的批评（[Wiley 综述](https://onlinelibrary.wiley.com/doi/full/10.1155/hbe2/9946143) `disputed`）；也有研究者反驳该批评（[Zenodo 2026](https://zenodo.org/records/19239521) `disputed`）。

这支撑 `answer.md` 的谨慎立场：AI 是否“理解”人生意义仍无定论，因此本文把 AI 的作用限定为结构生成与估计，不预设其语义归属。该争议不改变 \(C_a\) 的必要性：无论 AI 是否有语义理解，主体承诺都是另一层条件。

### S9.5 来源清单（S9）

- Clark & Chalmers, “The Extended Mind,” *Analysis* 58（1998）。`canonical`
- Searle, “Minds, Brains, and Programs,” *Behavioral and Brain Sciences* 3（1980）。`canonical`
- Dreyfus, *What Computers Still Can't Do*（1972/1992）。`established`
- Bender et al., “On the Dangers of Stochastic Parrots,” *FAccT*（2021）。`disputed`

---

## S10. 自然生命、有限性与意义接口

### S10.1 死亡意识与意义建构

**恐怖管理理论**的大量实验显示，死亡显著性（mortality salience）会增强世界观防御、自尊寻求和文化认同（[TMT 与意义研究](https://europepmc.org/article/med/19785489) `empirical`；[死亡、生活、稀缺与价值](https://pubmed.ncbi.nlm.nih.gov/19883489/) `empirical`）。

这支撑 \(E\) 中有限时间 \(T_a\) 的必要性：死亡边界改变价值与意义的动态，一个没有终结结构的决策模型不足以描述人生观。

### S10.2 向死而在与本真性

**海德格尔**把此在描述为在世界中存在、朝向死亡的有限存在，焦虑揭示世界意义的整体性（[Being and Time 传统研究](https://www.degruyterbrill.com/document/doi/10.1515/opth-2020-0003/html?lang=en) `established`）。支撑 \(M_a\) 的现象学接口：意义的经验维度包含对有限性的先行把握，形式变量只能部分捕捉。

### S10.3 意义与责任

**Frankl** 的意义疗法传统主张：人在任何处境中都可以对意义发问并作出回应，意义包含责任维度（[Frankl 传统综述](https://www.kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART001394068) `established`）。支撑 \(C_a\) 的承担维度：把某目的纳入自己的生活是回应，而非纯粹的接收。

### S10.4 来源清单（S10）

- Heidegger, *Sein und Zeit*（1927）。`canonical`
- Frankl, *Man's Search for Meaning*（1946）。`canonical`
- Greenberg, Pyszczynski & Solomon, TMT 文献（1986 起）。`empirical`

---

## 11. 缺口登记：仍待补强的支撑

以下接口目前只有方向性支撑，若后续写作要求更强的论证，需补充具体来源：

- **课程教材接口**：人生观、目的、态度、价值在中国课程语境中的规范定义尚未接入，需教材原文作为 `given` 级来源。
- **儒家修养传统接口**：目前仅有二手资料线索（[民主式自我修养研究](https://brill.com/view/journals/bire/1/4/article-p626_626.xml) `established`），如需引《论语》修身—立志—反省的经典文本，应补充原文卷章。
- **AI 影响的纵向证据**：S9 的实证研究多为单次说服实验；AI 长期参与对价值观形成的纵向证据仍少，需标注 `empirical/lacking`。
- **多目标优化的形式方法**：\(\Gamma_a\to2^{\mathcal F}\) 与多目标优化、约束满足的衔接只完成了方向性定位，需补充形式文献。
- **\(C_a\) 的操作化测量**：承诺判据如何用访谈、行为追踪或叙事分析测量，需心理测量与方法论文献。

## 12. 结论

`answer.md` 的根基结构现在具有两类外部支撑：

1. **经典文本与公认哲学立场**：期望效用公理化、实然—应然区分、假言/定言命令、二阶意愿、自欺、延伸心智、向死而在、叙事同一性等，为各形式对象提供概念来源。
2. **经验科学事实**：前景理论、显示偏好、Schwartz 价值观结构、SDT、意向—行动差距、认知失调、意义三成分、默认效应、LLM 说服等，为结构关系提供可检验约束。

未闭合之处被集中登记：教材语境、儒家传统、AI 纵向证据、形式优化衔接与承诺测量。这些缺口属于论据接口层，不改变 `algorithm.md` 与 `answer.md` 的语义闭合。
