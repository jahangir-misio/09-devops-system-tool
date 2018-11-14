## 项目与开发管理

### 1. 项目管理（未确定编写专家）

项目管理xxxx。

##### 应包含以下基本功能：

——xxxx

——xxxx

##### 可以包含以下高级功能：

——xxxx

——xxxx

### 2. 需求管理（未确定编写专家）

需求管理xxxx。

##### 应包含以下基本功能：

——xxxx

——xxxx

##### 可以包含以下高级功能：

——xxxx

——xxxx

### 3. 计划与任务管理

计划与任务管理是对于项目与开发过程中所有计划与任务的管理活动。

##### 应包含以下基本功能：

——开发计划管理宜支持看板协作项目计划管理与Scrum项目计划管理【仅描述看板协作与Scrum是否过于局限】

—— 【**建议增加：任务需要与项目、需求、缺陷等关联**】

——支持迭代/里程碑规划，创建、修改、删除、查询

——支持面向任务及面向迭代的视图迭代规划

——支持展示按迭代/里程碑展示任务

——支持创建、修改、删除、查询任务管理

——任务参数字段宜包含：标题、类型、标签、描述、优先级、重要程度、处理人、抄送人、项目、状态、迭代、父任务项、计划日期、预计工时、实际工时、发布版本、附件、完成度。

——支持任务拆分子任务

——支持为任务添加关联任务

——支持任务指派、再指派、认领、二次认领

——支持记录任务的状态，如：未开始、进行中、已完成

——支持可视化的任务跟踪，如：看板

——支持任务列表的导入导出

——支持以树形视图或表格视图式呈现的任务项列表

——提供多维度的项目统计报表，展现项目宏观和微观进展

##### 可以包含以下高级功能：

——支持【任务/】迭代/里程碑关联源代码对应分支，关联对应分支的CI/CD运行结果

——支持【任务/】迭代/里程碑自定义配置关联的资源，如文档文件

——支持设置迭代/里程碑的查看、添加、修改、删除权限【**建议调整为统一功能**】

——支持批量编辑任务、任务处理人及状态

——支持任务添加富文本信息

——支持设置任务参数显示列【**建议更加清楚的描述**】

——支持设置任务上传附件的数量与大小【**建议删除**】

——支持对任务进行评论

——支持按自定义条件筛选任务集【**什么是任务集，且是否有必要将任务集群管理**】

——支持以看板、表格方式展示任务集

——支持以不同属性维度对任务集进行分组，排序后展示

——支持设置任务的查看、添加、修改、删除权限【**建议调整为统一功能**】

——支持任务配置状态工作流

——支持状态工作流设置状态变更权限

——支持任务变更/分派/逾期消息【通知】机制

——支持任务操作日志

——支持用户自定义仪表盘，将用户关注的信息整合到一个页面上显示

——提供二次开发的API接口

### 

### 4. 文档与知识管理

文档与知识管理是对针对文档和知识的管理活动，应包含文档管理和知识管理两个部分。

#### 4.1 文档管理

文档是产品交付的核心研发资产之一。常见文档类型包括架构设计文档、用户帮助手册、系统原型文档等。常见文档格式包括微软Office
WORD/PPT/EXCEL、PDF、WPS Office文档、JPG等格式的图片文档。

##### 应包含以下基本功能：

——支持用户按照一定的目录结构对各种文档进行分门别类地管理

——支持通过批量上传本地目录或文件至文档管理服务中

——支持批量下载文档

——支持常见格式文档的在线预览

——支持文档版本管理，用户可以选择文档的某个版本进行过查看、下载等操作

——支持搜索功能，用户可以通过文件名或文件名关键字等快速查找到所需的文档

##### 可以包含以下高级功能：

——支持本地与远端文件的同步【**建议删除**】

——支持回收站功能，以防止用户误删除文档

——支持文档的在线编辑及多人并行编辑

——支持对文件内容进行搜索

——支持共享功能，可以在不同用户之间进行共享【**共享的含义比较模糊，是权限控制还是为分享？**】

#### 4.2 知识管理

知识管理涵盖产品交付过程中个人或者团队的各种知识内容，例如会议纪要、版本ReleaseNotes、技术材料等等。

##### 应包含以下基本功能：

——支持词条创建、编辑

——支持多人协同编辑

——支持词条分享

——支持搜索

——可导出为常见文档格式（例如Word、pdf）

——宜支持Wiki格式 



### 5. 团队协同

团队协同是将同一个开发组织内不同角色、不同个体、不同阶段的资源整合形成协同效应，可以增加研发组织的信息透明度和信息流动速度，实现组织决策的高效和准确性。



##### 应包含以下基本功能：

——支持将研发工作过程、工作结果在组织内进行公开展示

——支持将项目规划、需求、工作项、代码、测试用例、缺陷、构建任务、部署任务、流水线任务等向指定人员开放展示

——支持不同角色基于工件进行协作

——支持多角色协作进行分析需求、工作项流转、代码合并、主流代码分支模型、代码评审、多语言并行构建、依赖包管理、镜像仓库等工作

——支持团队仪表盘、项目仪表盘、可视化看板、Wiki、文档管理、Git代码仓库、聊天室等团队协同工具，以将度量数据标准化一致呈现给所有角色和个体、分享知识经验、信息透明传递。

——支持记录所有人在平台上的所有操作，以回溯经验和教训，并满足审计合规

##### 可以包含以下高级功能：

——xxxx

——xxxx



### 

### 6. 统计度量

统计度量是对DevOps过程的进度、质量、效率相关数据化指标展示。

##### 应包含以下基本功能：

——进度相关指标【包含但不仅限于】：需求累计流图、缺陷趋势图、需求完成数、新建缺陷数。

——【董越】进度相关指标：包括但不限于需求累计流图、缺陷趋势图、需求完成数、新建缺陷数。

——代码内在质量相关指标【包含但不仅限于】：包括但不限于代码质量、千行代码bug率、缺陷Reopen率、测试通过率。

——【董越】代码内在质量相关指标：包括但不限于代码质量、千行代码bug率、缺陷Reopen率、测试通过率。

——交付外在质量相关指标【包含但不仅限于】：包括但不限于故障率、线上问题率、发布回滚率。

——【董越】交付外在质量相关指标：包括但不限于故障率、线上问题率、发布回滚率。

——需求交付时长相关指标【包含但不仅限于】：需求从提交到交付的时长。

——【董越】需求交付时长相关指标：包括但不限于需求从提交到交付的时长。

——缺陷解决时长相关指标【包含但不仅限于】：包括但不限于缺陷从创建到关闭的平均时长，表征解决缺陷的效率。

——【董越】缺陷解决时长相关指标：包括但不限于缺陷从创建到关闭的平均时长，表征解决缺陷的效率。

——代码交付时长相关指标【包含但不仅限于】：代码从提交到交付的时长。

——【董越】代码交付时长相关指标：包括但不限于代码从提交到交付的时长。

——人效相关指标【包含但不仅限于】：对使用人员的基本产出能力度量， 包括但不限于完成需求数、解决缺陷数、完成任务数、提交代码量。

——【董越】人效相关指标：对使用人员的基本产出能力度量， 包括但不限于完成需求数、解决缺陷数、完成任务数、提交代码量。

——【董越】统计度量的维度：项目维度的统计和度量。个人维度的统计和度量。（项目维度和个人维度等描述不好理解9.27）

——【董越】统计度量的维度【包含但不仅限于】：项目维度的统计和度量，即统计特定项目的进度、需求交付时长等相关指标。个人维度的统计和度量，即统计特定个人的代码内在质量、人效等相关指标。（项目维度和个人维度等描述不好理解9.27）

——【董越】统计度量的维度：项目维度的统计和度量，即统计特定项目的进度、需求交付时长等相关指标。个人维度的统计和度量，即统计特定个人的代码内在质量、人效等相关指标。

##### 可以包含以下高级功能：

——进度相关指标：迭代燃尽图、需求控制图。【这是展示方式不是指标】

——【董越】进度相关指标：通过迭代燃尽图、需求控制图等方式展示。

——需求交付时长相关指标：对需求每个阶段的度量，包括但不限于需求响应时长、需求分析时长、需求设计时长、需求排期时长、需求开发时长。通过各种时长，能够定位需求交付瓶颈角色，用于改进。

——代码交付时长相关指标：对交付上线的每个阶段进行分解。包括但不限于代码提交、构建、单测、集成、部署、集成测试时长、等待时长。能够定位和反交付过程中的各个步骤，用于改进交付过程。

——人效相关指标：人力分配和人力负载的度量。人力分配：包括但不限于每个项目的真实人员投入量。人力负载：包括但不限于项目并发度、需求并发度。

——统计度量的维度：组织维度的统计和度量，即从企业组织架构和团队维度提供整体的统计和客观的分析。【董越】应用交付过程的效率和质量透明。应用维度的度量，即应用交付过程的效率和质量透明。

### 

### 7. 项目集管理

项目集管理对项目集运作过程中，项目、子项目集的运作情况进行管理的活动。

##### 应包含以下基本功能：

——项目集中可以包含多个项目和子项目集

——设置项目集PM，以及其他参与人

——设置以及展示项目集的进度、健康度【**请详细解释设置的含义，由于与任务与计划管理中进度相关联**】

——设置里程碑，分配负责人【**项目集有里程碑吗？**】

——录入需求、任务【**建议调整为录入或关联需求与任务**】

——填写及展示项目集的进度、健康度

——录入或关联需求任务

——记录跟踪项目集风险【**请解释如何进行风险管理**】

——展示它包含的所有项目或项目集的进展情况

——里程碑快到期发送消息通知给PM和里程碑负责人。

##### 可以包含以下高级功能：

——项目或项目集，可以属于多个项目集；

——树形展示项目集中包含的项目和子项目集，子项目集可以逐层下钻；

——包含的项目和子项目集中的里程碑和需求任务等在同一甘特图中展示；

——根据里程碑进展、需求任务完成情况，以及包含项目和子项目集的进度和健康度，自动计算项目集的进度和健康度；

——汇总包含的项目和子项目集中的需求、任务、风险；【**是否有必要？**】

——包含的项目和子项目集中的风险，可以自行决定是否透出到项目集中；
