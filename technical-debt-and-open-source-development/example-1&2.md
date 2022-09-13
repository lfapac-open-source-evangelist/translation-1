# 示例 1：自定义构建系统的作用

维护操作系统不仅仅是一项全职工作。需要确保：

- 随着时间的推移，它一直在安全可靠地运行；
- 随着时间的推移，每个组件都可以重新构建；
- 对每个组件都进行了适当的评估和测试；
- 尊重许可证，并且；
- 拥有强大且安全的更新机制。

这种类型的工作被低估了，因为现在可以在几个小时内完成一个Linux环境的搭建。然而，这只是长期维护操作系统的第一步。如今，随着ARM进入服务器市场，嵌入式设备的标准化分布变得更加容易。如Debian、Ubuntu、Redhat和SuSE等操作系统提供了在任何嵌入式设备上运行良好或稍作调整的ARM服务器发行版，并且无需维护自定义操作系统和相关的软件包构建。它还为开发人员提供标准化工具，将知识从云环境迁移至嵌入式市场中。随着招聘经理可以接入更大的市场——Linux服务器市场，寻找能够通过嵌入式系统工作的开发人员变得更加容易。 

嵌入式设备开发的一个重要趋势很可能是选择具有某种长期支持的ARM服务器发行版，以及以更高级别语言编写（与云计算行业大体相同的编写方式）的小型服务。Python、Node.js和Go在嵌入式系统行业都有光明的未来。下次您有嵌入式Linux项目时，请考虑使用标准Linux发行版，该发行版提供某种形式的长期支持并会减少您未来的技术债务。

# 示例 2：用户界面框架

收集一些开源组件并在Linux内核上运行它们是很容易的，这种组合就是Linux发行版。在屏幕上显示配有文字的图片并不是很困难，这就是所谓的小型UI框架。就像维护Linux发行版是一项永无止境的工作一样，编写和维护您的UI框架也将是一项永无止境的工作。请想一想这些需求：正确显示世界各地的语言、可访问性、扩大规模和适应有更多限制的环境，以及随着技术进步对不同渲染系统的支持。维护任何UI框架都没有止境。您可以很容易地在现有UI框架的发展过程中观察到这些。Qt、GTK和EFL至今已有20多年的历史。他们需要数百名开发人员才能达到他们现在的水平，我们应该预料到，在接下来的20年里，他们需要同样的努力程度。React和React Native也需要数百名开发人员，语言更改不会改变处理所有这些外部约束的需求。当你选择了一个UI框架时，要明白你选择了一个社区，并依靠他们来承担相应的技术债务。为了确保这个社区保持健康并不断帮你摆脱债务，你能够介入社区并提供帮助可能是必要的。 

另一个建议是需要注意有效的许可证以及任一具体项目的IP资产的拥有者通常是谁。在依赖于某一个 UI 框架、不参与其开发和未支付任何许可费用的前提下，如果您正在制作可视化应用程序，那么这在本质上会削弱您的核心依赖项之一，从而增加您的技术债务。切换框架通常很困难，而且您的应用程序越复杂，更改框架就越困难。就Linux发行版而言，您应该会希望以某种形式参与上游依赖项，以符合您自己的长远需求。对上游的贡献可以采取多种不同的形式，您应该选择与您的业务最匹配的一种（代码、货币、文档、营销等）。