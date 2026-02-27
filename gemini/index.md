# context 上下文
## gemini cli 的全局上下文模本

1. 配置
[gemini cli 的全局指令模版](gemini.global.template.md)， 配置位置：用户根目录 ~/.gemini/GEMINI.md

2. 启用
在终端， 项目文件夹下输入 gemini进入后，自动启用了全局指令模版， 可通过 /memory show 查看当前的上下文指令

## 项目上下文
1. 配置
在已有项目中， 通过/init 由AI自动生成

# skills 技能
1. 查看当前的技能列表
/skills list

2. 启用技能
/skills enable <skill_name>

3. 禁用技能
/skills disable <skill_name>

4. 编写技能
技能存放位置：~/.gemini/skills

5. 已经编写的技能
- tp-engineer
    tp是 task planning的缩写,这是一个复杂任务管理协议。当用户输入暗号 "@tp"、提到 "规划"、"Plan" 或涉及多文件重构时激活。此时进入任务规划模式，AI会在根目录创建一个IMPLEMENTATION_PLAN.md文件，跟无输入的需求，生成待执行的任务列表，在执行阶段逐个去执行任务列表中的任务