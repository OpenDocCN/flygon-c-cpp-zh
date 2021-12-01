# 第 3 部分:收获函数式编程的好处

我们已经学习了很多关于函数式编程的构建块，如何用 C++编写它们，以及如何使用它们来构建以函数为中心的设计。是时候看看一些与函数式编程密切相关的专业主题了。

首先，我们将深入探讨性能优化这个巨大的话题。我们将学习一些特别适合纯函数的优化技术(例如，记忆化和尾部递归优化)。我们将研究内存占用和执行时间优化，执行许多测量，并比较各种方法。

然后，我们将研究函数式编程如何实现并行和异步执行。不变性导致共享状态的避免，因此导致更简单的并行执行模式。

但是我们可以利用更多的函数式编程。数据生成器和纯函数实现了一个名为**基于属性测试**的自动化测试范例，它允许我们用很少的代码检查许多可能的场景。然后，如果我们需要重构复杂的现有代码，我们将看到我们可以首先将其重构为纯函数，快速为它们编写测试，然后决定是将它们重新分布到类中还是保留它们。

最后，我们将更上一层楼，到一个基于不可变状态的架构范例，因此，与功能编程紧密相连的东西:事件源。

本节将涵盖以下章节:

*   [第十章](10.html)、*性能优化*
*   [第 11 章](11.html)*物业测试*
*   [第 12 章](12.html)、*重构到纯函数*
*   [第 13 章](13.html)、*不变性和架构-事件源*