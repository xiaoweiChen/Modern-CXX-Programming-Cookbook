# Modern C++ Programming Cookbook
*Third Edition*

***精通现代C++与掌握C++23最新特性的140多种实用技巧***<a href=""><img src="cover.png" height="256px" align="right"></a>

* 作者：Marius Bancila
* 译者：陈晓伟
* Packt Publishing Ltd. (出版于: 2024年2月29日)

> [!IMPORTANT]
> 翻译是译者用自己的思想，换一种语言，对原作者想法的重新阐释。鉴于我的学识所限，误解和错译在所难免。如果你能买到本书的原版，且有能力阅读英文，请直接去读原文。因为与之相较，我的译文可能根本不值得一读。
>
> <p align="right"> — 云风，程序员修炼之道第2版译者</p>

## 本书概述

第三版的更新内容涵盖了 C++23 的最新特性，如堆栈库、expected 和 mdspan 类型、span 缓冲区、格式化库的改进，以及范围库的更新。此外，还探讨了之前未涉及的一些 C++20 特性，例如：同步输出流和 source_location。

本书按照实用示例的形式编排，涵盖了很多实际问题，能助各位快速找到所需的解决方案。书中全面覆盖了现代 C++ 编程的所有核心概念，以及从 C++11 到 C++23 的特性和技术，能够通过学习融入最新的语言和库改进，保持领先。

除了核心概念和新特性之外，还将探索与性能和最佳实践相关的示例，了解如何实现诸如 pimpl、命名参数、律师-客户模式和工厂模式等模式和惯用法，以及如何使用主流的 C++ 测试库——Boost.Test、Google Test 和 Catch2 完成单元测试。

到书末时，凭借这本书提供的全面覆盖，各位读者将拥有构建高效、可扩展，且性能优异的应用程序所需的一切知识。

## 作者简介

**Marius Bancila**是一位拥有二十余年经验的软件工程师，专注于为商务应用及其他领域开发解决方案，也是《Template Metaprogramming with C++》和《The Modern C++ Challenge》的作者。作为一名软件架构师，专注于Microsoft的技术，主要使用C++和C\#开发。Marius对于分享自己的技术专长充满热情，因此自2006年起，他因在C++和开发者技术领域的贡献而被授予Microsoft MVP称号。Marius居住在罗马尼亚，并在多个在线社区中保持活跃。



## 本书相关

* github翻译地址：https://github.com/xiaoweiChen/Modern-CXX-Programming-Cookbook

* 译文的LaTeX 环境配置：https://www.cnblogs.com/1625--H/p/11524968.html

  * 禁用拼写检查：https://blog.csdn.net/weixin_39278265/article/details/87931348

  * 使用xelatex编译时需要添加`-shell-escape`和`-8bit`选项，例如：

    `xelatex -synctex=1 -interaction=nonstopmode -shell-escape -8bit "Modern-CMake-for-C++-2ed".tex`

  * 为了内容中表格和目录索引能正常生成，至少需要连续编译两次

  * Latex中的中文字体([思源宋体](https://github.com/adobe-fonts/source-han-serif/releases))和英文字体([Hack](https://github.com/source-foundry/Hack-windows-installer/releases/tag/v1.6.0))，需要安装后自行配置。如何配置请参考主book/css.tex顶部关于字体的信息。

* vscode中配置LaTeX：https://blog.csdn.net/Ruins_LEE/article/details/123555016

