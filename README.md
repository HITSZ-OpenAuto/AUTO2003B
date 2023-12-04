# AUTO2003B - 创新训练课B

<!--
1. 通过 [Shields.io](https://shields.io/) 生成如下的徽章，标注课程的基本信息。
2. 请根据课程的具体内容增删仓库的子文件夹。子文件夹建议使用小写英文，并且添加 README.md。
3. 关于课程的描述可以不止以下几个方面，酌情增删。
4. hoa.moe 生成本课程对应页面后，请将页面链接复制到 GitHub 仓库的 About/Website 中。
5. 可以在 GitHub 页面的 About/Topics 中为课程添加话题名称。
-->

![考查课](https://img.shields.io/badge/%E8%80%83%E6%9F%A5%E8%AF%BE-green)
![学分1](https://img.shields.io/badge/%E5%AD%A6%E5%88%86-1-moccasin)

![成绩构成](https://img.shields.io/badge/%E6%88%90%E7%BB%A9%E6%9E%84%E6%88%90-gold)
![大作业100%](https://img.shields.io/badge/大作业-100%25-wheat)

## 课程介绍（摘自教学大纲）
本课程设计是在学生完成[高级语言程序设计](https://hoa.moe/docs/fresh-autumn/comp2021/)课程学习后进行的。
学生通过本课程的实践，能进一步掌握高级语言程序设计基本概念，掌握基本的程序设计方法；
通过设计一个完整的小型程序，给学生提供独立实践的机会，将课本上的理论知识和实际有机的结合起来，锻炼学生的分析解决实际问题的能力。
提高学生适应实际，实践编程的能力。
初步掌握开发软件所需的需求定义能力、功能分解能力和程序设计能力、代码调试技能；为未来的软件编程及其他课程的学习打下良好的基础。

翻译：
**自己动手制作一个程序**。

选题从课程给出的几个中选择一个，或者提交你自己的选题。

夏季学期结束时需提交开题报告；成果最后在大一立项结题的同时验收，需提交结题报告。

2022 级给出的选题有：
- 学院职工管理信息管理系统
- 学院学生信息管理系统
- 模拟地铁自动售票系统
- 贪吃蛇小游戏
- 跳棋游戏
- 简易三国杀游戏

## 授课教师

- Wu Xiaojun
  - 本课程与教师基本无关。

## 攻略

> by [@Maxwell Jay](https://github.com/MaxwellJay256), 2023.12

这应该是自动化学生为数不多的软件开发的机会。

### 挑选一个开发框架

**课程要求项目必须使用 `C/C++`**。
然而 `C/C++` 本身是没有办法制作 GUI 的，因此我们需要使用第三方库。

现代的桌面应用程序已经几乎不使用 `C/C++` 开发，但是为了降低学习成本，`C/C++` 仍是多数学生的唯一选择。

好在目前有不少基于 `C/C++` 的 GUI 开发框架可供选择，学习起来也不困难。
以下是教学大纲中提到的 4 个。
1. [EasyX](https://docs.easyx.cn/)：一个基于 `GDI+` 的图形库，比较古老了，使用简单，但是功能有限。
2. [Qt](https://www.qt.io/)：跨平台的 GUI 开发框架，功能强大，几乎可以做任何事情。并且你校学生证可以申请到 Qt 的教育许可证，解锁完整特性。
3. [MFC(Microsoft Foundation Classes)](https://learn.microsoft.com/zh-cn/cpp/mfc/mfc-desktop-applications)：一组封装了 C++ 类库的 Windows 编程框架，优点是兼容从 Win95 至今的所有 Windows 操作系统，且运行效率非常高；缺点是开发效率低，并且只能在 Windows 上运行。
4. [C#](https://learn.microsoft.com/dotnet/csharp/)：微软推出的一种面向对象的编程语言，语法类似于 `C/C++`，但是更加简洁，配合 UWP 或 WPF 可以开发出非常现代化的桌面应用程序。

个人推荐前 2 个。

### IDE

由于整个项目将会是一个大型工程，因此可以使用 [Visual Studio](https://visualstudio.microsoft.com) 作为你的 IDE 。
Visual Studio 也是 MFC 或 C# 的最佳选择。

Qt 有自己的 IDE [Qt Creator](https://www.qt.io/product/development-tools)，适合学习和实操 Qt 时使用。

### 选题

图省事的话推荐贪吃蛇，借助 AI 不到 1 天就能速通。

如果想多积累一点敲代码经验，可以选择客户端类型的软件（信息管理系统、售票系统），体验一下前、后端的开发思想，尤其是 GUI 该怎么设计才能中看又中用。
