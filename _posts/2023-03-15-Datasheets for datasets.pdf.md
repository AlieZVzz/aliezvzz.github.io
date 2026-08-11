---
layout: post
title: Datasheets for datasets
date: 2023-03-15
Author: aliezvzz
categories: 
tags: [人本 AI]
comments: False
--- 
Gebru, T., Morgenstern, J., Vecchione, B., Vaughan, J. W., Wallach, H., III, H. D., & Crawford, K. (2021). Datasheets for datasets. Communications of the ACM, 64(12), 86–92. https://doi.org/10.1145/3458723


<span class="highlight">“The characteristics of these datasets fundamentally influence a model’s behavior: a model is unlikely to perform well in the wild if its deployment context does not match its training or evaluation datasets, or if these datasets reflect unwanted societal biases”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 86</span>)</span> 这些数据集的特征从根本上影响模型的行为：如果模型的部署上下文与其训练或评估数据集不匹配，或者如果这些数据集反映了不需要的社会偏见，则模型不太可能在野外表现良好

<span class="highlight">“By analogy, we propose that every dataset be accompanied with a datasheet that documents its motivation, composition, collection process, recommended uses, and so on. Datasheets for datasets have the potential to increase transparency and accountability within the machine learning community, mitigate unwanted societal biases in machine learning models, facilitate greater reproducibility of machine learning results, and help researchers and practitioners to select more appropriate datasets for their chosen tasks.”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 86</span>)</span> 以此类推，我们建议每个数据集都附有一个数据表，记录其动机、组成、收集过程、推荐用途等。数据集的数据表有可能提高机器学习社区的透明度和问责制，减轻机器学习模型中不必要的社会偏见，促进机器学习结果的更大可重复性，并帮助研究人员和从业者为他们选择的任务选择更合适的数据集。

<span class="highlight">“For dataset consumers, the primary objective is to ensure they have the information they need to make informed decisions about using a dataset. Transparency on the part of dataset creators is necessary for dataset consumers to be sufficiently well informed that they can select appropriate datasets for their chosen tasks and avoid unintentional misuse.a”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 87</span>)</span> 对于数据集消费者，主要目标是确保他们拥有所需的信息，以便就使用数据集做出明智的决定。数据集创建者的透明度对于数据集消费者充分了解他们可以为他们选择的任务选择合适的数据集并避免无意滥用是必要的。

<span class="highlight">“There are currently no industry standards for documenting machine learning datasets.”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 87</span>)</span> 目前没有用于记录机器学习数据集的行业标准。

<span class="highlight">“Datasheets address this gap by documenting the contexts and contents of datasets: from their motivation, composition, collection process, and recommended uses.”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 87</span>)</span> 数据表通过记录数据集的上下文和内容来弥补这一差距：从它们的动机、组成、收集过程和推荐用途。

<span class="highlight">“Datasheets for datasets can increase transparency and accountability within the machine learning community, mitigate unwanted biases in machine learning models, facilitate greater reproducibility of machine learning results, and help researchers and practitioners to choose the right dataset.”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 87</span>)</span> 数据集的数据表可以提高机器学习社区的透明度和问责制，减少机器学习模型中不必要的偏见，促进机器学习结果的更大可重复性，并帮助研究人员和从业者选择正确的数据集。

<span class="highlight">“Datasheets enable dataset creators to be intentional throughout the dataset creation process.”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 87</span>)</span> 数据表使数据集创建者能够在整个数据集创建过程中有意识地进行。

<span class="highlight">“Iterating on the design of datasheets with practitioners and legal experts helped improve the questions.”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 87</span>)</span> 与从业者和法律专家一起反复设计数据表有助于改进问题。

<span class="highlight">“Datasheets and other forms of data documentation are increasingly commonly released along with datasets.”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 87</span>)</span> 数据表和其他形式的数据文档越来越普遍地与数据集一起发布。

<span class="highlight">“1. For what purpose was the dataset created? Was there a specific task in mind? Was there a specific gap that needed to be filled? Please provide a description.”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 88</span>)</span> 1. 创建数据集的目的是什么？有什么具体的任务吗？是否有需要填补的具体差距？请提供描述。

<span class="highlight">“2. Who created the dataset (for example, which team, research group) and on behalf of which entity (for example, company, institution, organization)?”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 88</span>)</span> 2. 谁创建了数据集（例如，哪个团队、研究小组）并代表哪个实体（例如，公司、机构、组织）？

<span class="highlight">“3. Who funded the creation of the dataset? If there is an associated grant, please provide the name of the grantor and the grant name and number.”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 88</span>)</span> 3. 谁资助了数据集的创建？如果有关联的赠款，请提供赠款人的姓名以及赠款名称和编号。

<span class="highlight">“4. Any other comments?”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 88</span>)</span> 4. 还有其他意见吗？

<span class="highlight">“In this section, we provide a set of questions designed to elicit the information that a datasheet for a dataset might contain, as well as a workflow for dataset creators to use when answering these questions. The questions are grouped into sections that approximately match the key stages of the dataset lifecycle: motivation, composition, collection process, preprocessing/cleaning/labeling, uses, distribution, and maintenance. This grouping encourages dataset creators to reflect on the process of creating, distributing, and maintaining a dataset, and even alter this process in response to their reflection.”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 88</span>)</span> 在本节中，我们提供了一组旨在引出数据集数据表可能包含的信息的问题，以及供数据集创建者在回答这些问题时使用的工作流程。这些问题被分为大致匹配数据集生命周期关键阶段的部分：动机、组成、收集过程、预处理/清理/标记、使用、分发和维护。这种分组鼓励数据集创建者反思创建、分发和维护数据集的过程，甚至根据他们的思考改变这个过程。

<span class="highlight">“We note that not all questions will be applicable to all datasets; those that do not apply should be skipped.”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 88</span>)</span> 我们注意到并非所有问题都适用于所有数据集；那些不适用的应该被跳过。

<span class="highlight">“5. What do the instances that comprise the dataset represent (for example, documents, photos, people, countries)? Are there multiple types of instances (for example, movies, users, and ratings; people and interactions between them; nodes and edges)? Please provide a description.”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 89</span>)</span> 5. 构成数据集的实例代表什么（例如，文件、照片、人物、国家）？是否有多种类型的实例（例如，电影、用户和评级；人和他们之间的交互；节点和边缘）？请提供描述。

<span class="highlight">“6. How many instances are there in total (of each type, if appropriate)?”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 89</span>)</span> 6. 总共有多少个实例（每种类型，如果适用）？

<span class="highlight">“7. Does the dataset contain all possible instances or is it a sample (not necessarily random) of instances from a larger set? If the dataset is a sample, then what is the larger set? Is the sample representative of the larger set (for example, geographic coverage)? If so, please describe how this representativeness was validated/ verified. If it is not representative of the larger set, please describe why not (for example, to cover a more diverse range of instances, because instances were withheld or unavailable).”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 89</span>)</span> 7. 数据集是否包含所有可能的实例，或者它是来自更大集合的实例样本（不一定是随机的）？如果数据集是样本，那么更大的集合是什么？样本是否代表更大的集合（例如，地理覆盖范围）？如果是，请说明如何验证/验证这种代表性。如果它不能代表更大的集合，请说明为什么不（例如，为了涵盖更多样化的实例，因为实例被保留或不可用）。

<span class="highlight">“8. What data does each instance consist of? “Raw” data (for example, unprocessed text or images) or features? In either case, please provide a description.”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 89</span>)</span> 8.每个实例包含哪些数据？ “原始”数据（例如，未处理的文本或图像）或特征？无论哪种情况，请提供说明。

<span class="highlight">“9. Is there a label or target associated with each instance? If so, please provide a description.”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 89</span>)</span> 9. 是否有与每个实例关联的标签或目标？如果有，请提供说明。

<span class="highlight">“10. Is any information missing from individual instances? If so, please provide a description, explaining why this information is missing (for example, because it was unavailable). This does not include intentionally removed information, but might include, for example, redacted text.”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 89</span>)</span> 10.个别情况是否遗漏任何信息？如果是，请提供描述，解释缺少此信息的原因（例如，因为它不可用）。这不包括有意删除的信息，但可能包括，例如，编辑文本。

<span class="highlight">“11. Are relationships between individual instances made explicit (for example, users’ movie ratings, social network links)? If so, please describe how these relationships are made explicit.”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 89</span>)</span> 11. 个体实例之间的关系是否明确（例如，用户的电影评级、社交网络链接）？如果是，请描述这些关系是如何明确的。

<span class="highlight">“12. Are there recommended data splits (for example, training, development/validation, testing)? If so, please provide a description of these splits, explaining the rationale behind them.”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 89</span>)</span> 12. 是否有建议的数据拆分（例如，培训、开发/验证、测试）？如果是这样，请提供这些拆分的描述，并解释其背后的基本原理。

<span class="highlight">“14. Is the dataset self-contained, or does it link to or otherwise rely on external resources (for example, websites, tweets, other datasets)? If it links to or relies on external resources, a) are there guarantees that they will exist, and remain constant, over time; b) are there official archival versions of the complete dataset (that is, including the external resources as they existed at the time the dataset was created); c) are there any restrictions (for example, licenses, fees) associated with any of the external resources that might apply to a dataset consumer? Please provide descriptions of all external resources and any restrictions associated with them, as well as links or other access points, as appropriate.”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 89</span>)</span> 14. 数据集是独立的，还是链接到或以其他方式依赖外部资源（例如，网站、推文、其他数据集）？如果它链接到或依赖外部资源，a) 是否保证它们会存在并随着时间的推移保持不变； b) 是否有完整数据集的官方存档版本（即包括创建数据集时存在的外部资源）； c) 是否存在与可能适用于数据集消费者的任何外部资源相关的任何限制（例如，许可、费用）？请酌情提供所有外部资源的描述和与之相关的任何限制，以及链接或其他访问点。

<span class="highlight">“15. Does the dataset contain data that might be considered confidential (for example, data that is protected by legal privilege or by doctor–patient confidentiality, data that includes the content of individuals’ non-public communications)? If so, please provide a description.”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 89</span>)</span> 15. 数据集是否包含可能被视为机密的数据（例如，受法律特权或医患保密保护的数据，包括个人非公开通信内容的数据）？如果有，请提供说明。

<span class="highlight">“16. Does the dataset contain data that, if viewed directly, might be offensive, insulting, threatening, or might otherwise cause anxiety? If so, please describe why.”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 89</span>)</span> 16. 数据集是否包含如果直接查看可能具有冒犯性、侮辱性、威胁性或可能引起焦虑的数据？如果是，请说明原因。

<span class="highlight">“17. Does the dataset identify any subpopulations (for example, by age, gender)? If so, please describe how these subpopulations are identified and provide a description of their respective distributions within the dataset.”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 89</span>)</span> 17. 数据集是否识别任何亚群（例如，按年龄、性别）？如果是这样，请描述这些亚群是如何被识别的，并提供它们在数据集中各自分布的描述。

<span class="highlight">“18. Is it possible to identify individuals (that is, one or more natural persons), either directly or indirectly (that is, in combination with other data) from the dataset? If so, please describe how.”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 89</span>)</span> 18. 是否可以从数据集中直接或间接（即结合其他数据）识别个人（即一个或多个自然人）？如果是，请描述如何。

<span class="highlight">“19. Does the dataset contain data that might be considered sensitive in any way (for example, data that reveals race or ethnic origins, sexual orientations, religious beliefs, political opinions or union memberships, or locations; financial or health data; biometric or genetic data; forms of government identification, such as social security numbers; criminal history)? If so, please provide a description.”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 89</span>)</span> 19. 数据集是否包含任何可能被认为敏感的数据（例如，揭示种族或民族起源、性取向、宗教信仰、政治观点或工会成员身份或位置的数据；财务或健康数据；生物特征或遗传数据数据；政府身份证明的形式，例如社会安全号码；犯罪记录）？如果有，请提供说明。

<span class="highlight">“27. Did you collect the data from the individuals in question directly, or obtain it via third parties or other sources (for example, websites)?”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 90</span>)</span> 27. 您是直接从相关人员那里收集数据，还是通过第三方或其他来源（例如网站）获取数据？

<span class="highlight">“28. Were the individuals in question notified about the data collection? If so, please describe (or show with screenshots or other information) how notice was provided, and provide a link or other access point to, or otherwise reproduce, the exact language of the notification itself.”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 90</span>)</span> 28. 是否已将数据收集通知相关人员？如果是，请描述（或显示屏幕截图或其他信息）如何提供通知，并提供链接或其他访问点，或以其他方式复制通知本身的确切语言。

<span class="highlight">“29. Did the individuals in question consent to the collection and use of their data? If so, please describe (or show with screenshots or other information) how consent was requested and provided, and provide a link or other access point to, or otherwise reproduce, the exact language to which the individuals consented.”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 90</span>)</span> 29. 相关个人是否同意收集和使用他们的数据？如果是，请描述（或显示屏幕截图或其他信息）如何请求和提供同意，并提供链接或其他访问点，或以其他方式复制个人同意的确切语言。

<span class="highlight">“30. If consent was obtained, were the consenting individuals provided with a mechanism to revoke their consent in the future or for certain uses? If so, please provide a description, as well as a link or other access point to the mechanism (if appropriate).”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 90</span>)</span> 30. 如果获得同意，是否为同意的个人提供了一种机制，可以在将来或针对某些用途撤销他们的同意？如果是，请提供描述，以及该机制的链接或其他访问点（如果适用）。

<span class="highlight">“31. Has an analysis of the potential impact of the dataset and its use on data subjects (for example, a data protection impact analysis) been conducted? If so, please provide a description of this analysis, including the outcomes, as well as a link or other access point to any supporting documentation”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 90</span>)</span> 31. 是否对数据集及其使用对数据主体的潜在影响进行了分析（例如，数据保护影响分析）？如果是，请提供此分析的描述，包括结果，以及指向任何支持文档的链接或其他访问点

<span class="highlight">“32. Any other comments?”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 90</span>)</span> 32. 还有其他意见吗？

<span class="highlight">“20. Any other comments?”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 90</span>)</span> 20. 还有其他意见吗？

<span class="highlight">“21. How was the data associated with each instance acquired? Was the data directly observable (for example, raw text, movie ratings), reported by subjects (for example, survey responses), or indirectly inferred/ derived from other data (for example, part-of-speech tags, model-based guesses for age or language)? If the data was reported by subjects or indirectly inferred/derived from other data, was the data validated/verified? If so, please describe how.”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 90</span>)</span> 21. 与每个实例相关的数据是如何获取的？数据是直接可观察的（例如，原始文本、电影评级）、受试者报告的（例如，调查回复），还是从其他数据间接推断/得出的（例如，词性标签、基于模型的猜测）年龄或语言）？如果数据是由受试者报告的或从其他数据间接推断/得出的，数据是否经过验证/验证？如果是，请描述如何。

<span class="highlight">“22. What mechanisms or procedures were used to collect the data (for example, hardware apparatuses or sensors, manual human curation, software programs, software APIs)? How were these mechanisms or procedures validated?”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 90</span>)</span> 22. 使用了哪些机制或程序来收集数据（例如，硬件设备或传感器、人工人工管理、软件程序、软件 API）？这些机制或程序是如何验证的？

<span class="highlight">“23. If the dataset is a sample from a larger set, what was the sampling strategy (for example, deterministic, probabilistic with specific sampling probabilities)?”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 90</span>)</span> 23. 如果数据集是来自更大集合的样本，抽样策略是什么（例如，确定性的、具有特定抽样概率的概率性）？

<span class="highlight">“24. Who was involved in the data collection process (for example, students, crowdworkers, contractors) and how were they compensated (for example, how much were crowdworkers paid)?”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 90</span>)</span> 24. 谁参与了数据收集过程（例如，学生、众包工作者、承包商）以及他们如何获得报酬（例如，众包工作者的报酬是多少）？

<span class="highlight">“25. Over what timeframe was the data collected? Does this timeframe match the creation timeframe of the data associated with the instances (for example, recent crawl of old news articles)? If not, please describe the timeframe in which the data associated with the instances was created”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 90</span>)</span> 25. 数据是在什么时间范围内收集的？此时间范围是否与实例关联数据的创建时间范围相匹配（例如，最近对旧新闻文章的抓取）？如果不是，请描述创建与实例相关的数据的时间范围

<span class="highlight">“26. Were any ethical review processes conducted (for example, by an institutional review board)?”</span> <span class="citation">(<span class="citation-item">Gebru et al., 2021, p. 90</span>)</span> 26. 是否进行了任何伦理审查程序（例如，由机构审查委员会）？
