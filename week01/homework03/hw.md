### **任务 1：定义 3 个 Agent 角色文件**

在你的知识库项目中创建 .opencode/agents/ 目录，编写 collector.md、analyzer.md、organizer.md 三个角色定义文件。每个文件必须包含：角色定义、权限声明（含原因）、工作职责、输出格式、质量自查清单。

- 生成collector.md

![1_1](img/1_1.png)

- 生成  analyzer.md、organizer.md

![1_1](img/1_2.png)

![1_1](img/1_3.png)



### 任务 2：用 OpenCode 测试触发 Sub-Agent

在 OpenCode 中依次用 @mention 委派三个 Agent 执行任务，观察每个 Agent 是否按角色定义执行、是否遵守权限指令、产出是否符合指定格式。记录遇到的问题和调整过程。

遇到的问题： 

- 第一个任务，没有写入功能，无法写入，然后AI会自己更改方式写入

![1_1](img/2_1.png)

- 保存的位置不对，保存到了根目录 （我手动放里面，然后继续）

![1_1](img/2_2.png)

- 任务2看不到详细的过程

![1_1](img/2_3.png)

- 任务3执行情况

![1_1](img/2_4.png)

![1_1](img/2_5.png)

- 输出日志

![1_1](img/2_6.png)



### **任务 3：（选做）设计第 4 个 Agent：Reviewer**

为知识库设计一个审核 Agent（reviewer.md），负责审核 Organizer 存入的知识条目质量。思考：它需要什么权限？在流水线的哪个位置？它的输入和输出分别是什么？

