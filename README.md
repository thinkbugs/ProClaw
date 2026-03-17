![image](https://raw.githubusercontent.com/thinkbugs/ProClaw/refs/heads/main/ProClaw-3.png)

ProClaw 🚀

Supercharge Your Potential. Build Your Digital Corps.<br>
激发你的潜能，构建你的数字军团。


The Operating System for the Super-Individual Era. 
开启超级个体时代的操作系统。<br>

ProClaw is not just another AI agent. It's your central command for a scalable, modular army of digital entities. 
ProClaw不只是另一个AI智能体。它是你指挥一支可扩展、模块化数字军团的中央司令部。<br>

It empowers you to transcend the limits of a single human and operate as a one-person powerhouse. 
它让你突破单一个体的极限，以一人之力，驾驭全局。

!demo-banner-placeholder.png

🌟 愿景 Vision: From Tool User to Force Multiplier

未来的工作不在于更快地完成更多任务，而在于重新定义单一个体所能实现的成就。
The future of work isn't about doing more tasks faster; it's about redefining what a single individual can achieve.

ProClaw 基于一个核心论点构建：AI时代最有价值的单元是超级个体——一个由个性化、可编排的AI能力网络增强的人。
ProClaw is built on a core thesis: the most valuable unit in the AI age is the Super-Individual—a person augmented by a personalized, orchestrated network of AI capabilities.

与仅仅执行命令的工具不同，ProClaw 帮助你架构、部署和指挥属于你自己的数字军团。
Unlike tools that simply execute commands, ProClaw helps you architect, deploy, and command your own digital corps.

✨ 核心特性 Core Features

ProClaw 提供了构建和管理你数字分体所需的一切。

•   🫀 中央指挥中心 (ProClaw Core)

    你的任务控制中枢。一个具备持久记忆和规划能力的“大脑”，理解复杂目标，管理跨会话状态，并协调你所有的专业智能体与技能。它是你永远不会遗忘上下文的战略伙伴。
    Your mission control. A persistent, planning-aware brain that understands complex goals, manages state across sessions, and coordinates all your specialized agents and skills.

•   ⚙️ 技能军火库与智能体工场 (ProClawHUB)

    你扩展能力的引擎。ProClawHUB 是一个充满活力的生态，让能力模块化、可组合。
    The engine of your expansion. ProClawHUB is a thriving ecosystem where capabilities are modular and composable.
    ◦ 技能市集 (Skill Marketplace): 瞬间装备专家级能力。从市集中查找、安装并使用社区构建或官方的技能插件，涵盖金融、设计、研究、法律等无数领域。将知识鸿沟转化为秒级解决的问题。
    Instantly equip expert-level abilities. Find, install, and use community-built or official Skill plugins for various domains.

    ◦ 定制智能体工厂 (Custom Agent Factory): 这是革命性的一步。克隆并规模化你的核心竞争力。 将你独特的方法论——无论是你的投资分析框架、内容创作风格还是客户服务流程——训练成可独立运行、自主工作的定制智能体。部署它们，分享它们，或让它们异步工作。这是你放大影响力的方式。
    Clone and scale your core competencies. Train your unique methodologies into standalone, autonomous Custom Agents.

•   🤝 进化共同体 (Super-Individual Camp) 超级个体营

    你并非独自构建。加入一个由先驱、建造者和领导者组成的先锋社区。
    You‘re not building alone. Join a vanguard community.
    
    ◦   共创 (Co-create) 未来工作模式。in exclusive workshops.
    ◦   连接 (Connect) 你的数字军团以应对复杂挑战。your digital corps with others for complex missions.
    ◦   学习 (Learn) 成功超级个体的思维与策略。the mindsets and strategies of successful super-individuals.

🚀 快速开始 Quick Start

在几分钟内启动并运行你的第一个数字智能体。

1.  安装 Installation
    # 通过 pip 安装 Install via pip
    pip install proclaw

    # 或从源码克隆并安装 Or clone and install from source
    git clone https://github.com/thinkbugs/proclaw/proclaw.git
    cd proclaw
    pip install -e .
    

2.  设置与认证 Setup & Authentication
    # 运行设置向导 Run the setup wizard
    proclaw init
    # 跟随提示配置你的环境和API密钥。Follow the prompts to configure your environment and API keys.
    

3.  运行你的第一个智能体 Run Your First Agent
    创建一个简单的 my_first_agent.py：
    from proclaw import Agent, Skill

    # 从HUB加载一个研究技能 Load a research skill from the HUB
    market_research = Skill.from_hub(“advanced-market-analysis”)

    # 定义你智能体的任务 Define your agent‘s mission
    @agent(mission=“Research the renewable energy tech landscape for Q2 2026”)
    def research_agent():
        data = market_research.execute(topic=“solid-state batteries”)
        return data.generate_report(format=“md”)

    # 部署它 Deploy it
    if __name__ == “__main__”:
        result = research_agent.run()
        print(result)
    
    运行：python my_first_agent.py

📁 项目结构 Project Structure


proclaw/<br>
├── core/                 # 中央指挥逻辑，记忆，规划器 Central command logic, memory, planner<br>
├── hub/                  # 技能市集 & 智能体工厂 SDK Skill marketplace & Agent factory SDK<br>
├── agents/               # 预构建和社区智能体库 Library of pre-built and community agents<br>
├── skills/               # 官方技能插件库 Library of official skill plugins<br>
├── docs/                 # 完整文档 Comprehensive documentation<br>
└── examples/             # 示例项目和教程 Example projects and tutorials<br>


🔧 如何贡献 How to Contribute

超级个体时代由社区共同构建。我们欢迎各种形式的贡献。The Super-Individual era is built by the community.
•   开发技能 (Build a Skill): 拥有小众专业知识？将其打包成HUB的技能插件。
• Package it into a Skill plugin for the HUB.

• 分享智能体 (Share an Agent): 开源你的定制智能体以启发他人。
• Open-source your custom agent to inspire others.

• 改进核心 (Improve the Core): 深入架构，帮助我们构建更强大的基础。
• Dive into the architecture and help us build a more robust foundation.

• 加入讨论 (Join the Discussion): 在我们的 你的邀请链接 或 链接 中分享你的使用场景和想法。

• 请阅读我们的 CONTRIBUTING.md 和 CODE_OF_CONDUCT.md。


📄 许可证 License

ProClaw 在 Apache License 2.0 下发布。详情见 LICENSE 文件。
ProClaw is released under the Apache License 2.0.

🫂 致谢与这场运动 Acknowledgments & The Movement

ProClaw 不止是代码。这是一场重新定义人类潜能运动的开始。它为拒绝被旧规则限制的先驱、创造者和建造者而生。
ProClaw is more than code. It‘s the beginning of a movement to redefine human potential.

这不是我们预测的未来，而是我们正在亲手建造的未来。
This isn‘t the future we predict. It‘s the future we‘re building.

准备好架构你的未来了吗？Ready to architect your future?

•   官网与文档 Website & Docs: https://proclaw.top

•   HUB 与社区 HUB & Community: https://hub.proclaw.top


在 GitHub 上给我们点个星 ⭐，共同踏上旅程，塑造工作的未来。
Star us on GitHub ⭐ to follow our journey and shape the future of work.
