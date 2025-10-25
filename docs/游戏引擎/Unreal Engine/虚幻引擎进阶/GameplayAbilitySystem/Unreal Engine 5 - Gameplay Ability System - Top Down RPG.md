# 🏫Unreal Engine 5 - Gameplay Ability System - Top Down RPG

页面贡献者：[Max1122Chen](https://github.com/Max1122Chen)

更新时间：2025.10.25

## 简介

- 类型：视频课程
- 主讲老师/作者：[Stephen Ulibarri](https://www.udemy.com/user/stephen-ulibarri-3/)
- 前置科技：UE基础知识，UE C++
- 级别：进阶级
- 难度：⭐ ⭐ ⭐ 
- 面向对象：虚幻引擎游戏开发工程师
- 所需工具：Unreal Engine 4.x/5.x, Visual Studio

本课程是虚幻引擎的官方系统性插件GameplayAbilitySystem（简称GAS）的入门教程。以下对GAS的介绍引自虚幻引擎官方文档：

> **Gameplay技能系统（Gameplay Ability System）** 是一种框架，用于编译[Actor](https://dev.epicgames.com/documentation/zh-cn/unreal-engine/actors-in-unreal-engine)可以拥有和触发的属性、技能和交互。该系统可适应各种各样的[Gameplay驱动型](https://dev.epicgames.com/documentation/zh-cn/unreal-engine/data-driven-gameplay-elements-in-unreal-engine)项目，例如 **角色扮演游戏** （RPG）、 **动作冒险（Action-Adventure）** 游戏和 **多玩家在线战术竞技** 游戏（MOBA）。
>
> 使用Gameplay技能系统，你可以：
>
> - 使用[技能系统组件](https://dev.epicgames.com/documentation/zh-cn/unreal-engine/gameplay-ability-system-component-and-gameplay-attributes-in-unreal-engine)。技能系统组件包括[Actor组件](https://dev.epicgames.com/documentation/zh-cn/unreal-engine/components-in-unreal-engine)实现的所有基础功能。
> - 技能系统组件实现了自己的[接口](https://dev.epicgames.com/documentation/zh-cn/unreal-engine/interfaces-in-unreal-engine)，以访问Gameplay技能系统的框架并与之交互。
> - 为Actor创建主动或被动[Gameplay技能](https://dev.epicgames.com/documentation/zh-cn/unreal-engine/gameplay-ability-system-for-unreal-engine)，使之与项目的Gameplay机制、[视觉效果](https://dev.epicgames.com/documentation/zh-cn/unreal-engine/creating-visual-effects-in-niagara-for-unreal-engine)、[动画](https://dev.epicgames.com/documentation/zh-cn/unreal-engine/animating-characters-and-objects-in-unreal-engine)、[声音](https://dev.epicgames.com/documentation/zh-cn/unreal-engine/working-with-audio-in-unreal-engine)和其他数据驱动型元素进行协作。
> - 使用[属性和属性集](https://dev.epicgames.com/documentation/zh-cn/unreal-engine/gameplay-attributes-and-attribute-sets-for-the-gameplay-ability-system-in-unreal-engine)，在它们与Gameplay技能系统交互时存储、计算和修改Gameplay相关值。
> - 使用[Gameplay效果](https://dev.epicgames.com/documentation/zh-cn/unreal-engine/gameplay-systems-in-unreal-engine)更改属性，通过项目的设计直接修改属性值。Gameplay效果包含可确定Gameplay效果行为的Gameplay效果组件。
> - [技能任务](https://dev.epicgames.com/documentation/zh-cn/unreal-engine/gameplay-ability-tasks-in-unreal-engine)（ `UAbilityTask` ）是处理Gameplay技能的一种专门形式的Gameplay任务类。使用Gameplay技能系统的游戏通常包括各种各样的自定义技能任务，它们实现了独特的Gameplay功能。它们在Gameplay技能执行期间执行异步工作，并能够在原生C++代码中调用委托或像[蓝图](https://dev.epicgames.com/documentation/zh-cn/unreal-engine/blueprints-visual-scripting-in-unreal-engine)那样在一个或多个输出执行引脚中移动来影响执行流程。
>
> 使用此系统，你可以创建单次攻击之类的技能，或添加更复杂的技能，例如根据来自用户和目标的数据触发许多状态效果的咒语。

通过使用GAS系统，你可以创建复杂且高度可扩展的游戏技能系统。目前比较有名的使用GAS系统开发的游戏有《堡垒之夜》和《漫威争锋》。

GAS系统是UE的一个相对较新的且复杂的系统，并且在持续更新迭代，目前网络上关于GAS的高质量的详细教程不多，而本教程算是网络上最好的GAS入门教程。

本课程长达106小时，对GAS系统的基本运用和最佳实践作了详细的介绍。作者作为Udemy上的专业讲师，课程设计合理，干货满满，全程没有半句废话。尽管理论上学习本课程需要学习者有UE C++的基础，但是作者在讲授时非常照顾潜在的小白，会对UE C++的一些基础进行讲解，笔者本人的UE C++水平就是在学习本课程时飞速进步的（虽然这样的学习路径似乎有些奇怪）。此外，除了GAS本身，课程还涵盖了非常多的程序设计思维、设计模式讲解、和开发最佳实践，对编程思维的提升也非常大。认真学习完本课程，并跟随老师一步步操作，你甚至可以完成一个有趣的小但充满技术含量的demo。



## 相关资源

- 课程主页：[Unreal Engine 5 - Gameplay Ability System - Top Down RPG | Udemy](https://www.udemy.com/course/unreal-engine-5-gas-top-down-rpg/?couponCode=KEEPLEARNING)

- [[中文直播\]第31期｜GAS插件介绍（入门篇） | 伍德 大钊_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV1X5411V7jh/?spm_id_from=333.999.0.0)
