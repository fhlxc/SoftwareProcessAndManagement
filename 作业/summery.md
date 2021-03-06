## 需求部分总结
### 一、软件需求定义
1. 为用户解决某一问题或达到某一目标所需的软件功能
2. 系统或系统构件为了满足合同、规约、标准或其他正式实行的文档而必须满足或具备的软件功能
### 二、软件需求活动
这个地方我特别疑惑，我上过软件需求分析这个课程，列出的五个活动与这个完全不一样，现列出需求分析中的五个活动，如下：  
1. 需求获取：与用户交流，对现有系统的观察及对任务进行分析，从而开发、捕获和修订用户需求
2. 需求建模：为最终用户所看到的系统建立一个概念模型，作为对需求的抽象描述，并尽可能多的捕获现实世界的语义
3. 形成需求规格：生成需求模型构件的精确的形式化的描述，作为用户和开发者之间的一个协约
4. 需求验证：以需求规格说明为输入，通过符号执行、模拟或快速原型等途径，分析需求规格的正确性和可行性
5. 需求管理：支持系统的需求演进，如需求变化和可跟踪性问题
### 三、需求类型区别部分需求
1. 业务需求：描述了组织为什么要开发一个系统，即组织希望达到的目标
2. 用户需求：描述了用户能使用系统来做些什么
3. 功能需求：描述是开发人员需要实现什么
4. 业务规则：常常会限制谁 能够执行某些特定用例，或者规定系统为符合相关规则必须实现某些特定功能
5. 非功能性需求：指依一些条件判断系统运作情形或其特性，而不是针对系统特定行为的需求
6. 外部接口需求：规约系统或系统构件与之交互的硬件、软件或数据库元素。
### 四、不同类型的用户
1. 主要用户：显示与产品交互的用户
2. 次要用户：偶尔使用产品或通过第三方与产品交互的用户
3. 三级用户：受产品使用影响或对产品作出决定的用户
### 五、整体过程详解
1. 获取需求：考虑什么问题问客户，什么不问，以获得准确的需求
2. 表达需求：通过UML、故事版、线框图等来描绘出需求
3. 用户故事：描述谁做什么为什么这么做
4. 产品积压和故事图：定需求优先级和管理需求
### 六、需求中常见的不明确语言
1. 客户满意——什么是满意的呢？
2. 快速响应——多快算快速呢？
3. 稳定运行——怎样说明稳定呢？
4. 有效控制——如何算有效？
### 七、如何识别模糊的语言
1. 是否描述明确
2. 是否含有具体指标
3. 是否具有二义性
### 八、用户限制
1. 时间
2. 消费
3. 价值
### 九、规避这些限制
1. 时间：让用户花更少的时间，体验更好的感觉，例如短视频、推荐
2. 价格：优化好功能，推出更好的功能，让用户花得实在
3. 价值：提炼核心功能，核心非功能要求，做到尽量最大化
- - -
## 计划部分总结
### 一、项目计划的关键点
把项目分成小的、更加易于管理的任务。
### 二、计划的工作
- 分解大的活动
- 详细地描述和组织任务
- 制定时间和工作预算
- 准确安排工作时间
### 三、release planning & iteration planning
比较因子 | release planning | iteration planning
:---- | :---- | :----
定义 |  整体计划项目 | 计划在特定迭代中完成的任务
技术 | 甘特图、发布计划 | PERT图表、CPM图表、迭代计划
### 四、术语总结
术语 | 含义
:--- | :---
任务 | 项目的一小步、可管理的部分
角色 | 一个人承担或扮演的职责
工作产品 | 一个任务或过程的产出物
时间表 | 任务到时间线的映射
里程碑 | 内部检查点以衡量进度
### 五、做软件的目标
1. 正确的产品
2. 做正确
3. 管理正确
### 六、对软件计划的看法
1. 问题定义  
做什么：背景，开发系统现状，开发条件和理由，总体要求，问题的性质，目标，条件，环境要求  
怎么做：  
I. 提取用户对问题要求  
II. 调查开发的背景理由  
III. 看用户报告  
IV. 加工整理  
V. 改进问题
VI. 满意文档
2. 可行性研究
做什么：辨别经济、技术、操作、法律、时间的可行性  
怎么做：  
I. 问题初认识：了解问题如何被提出、设法解决、了解问题结构  
II. 市场调查：需求情况、类似软件系统  
III. 分析准备：分析计划、分配职责  
IV. 环境分析：组织结构、软硬件、操作环境、规定的制约  
3. 计划内容
做什么：编写计划书  
怎么做：  
I. 软件范围：功能规模、软件对硬件需求  
II. 环境资源：人力、软件、进度表
4. 价格估计
做什么：进行软件成本的估算，价格因素——人口、产品、工程和资源  
怎么做：  
I. 参数化运算
II. 代码行价格估算：源代码行数、劳动时间长短、单位时间软件完成度、任务分解
5. 成本/收益分析
做什么：经济上整个软件是否划算  
怎么做：  
I. 成本估计：自顶向下、自底向上
II. 成本/效益分析法：运行费、经济收益