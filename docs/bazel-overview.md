
[原文链接](https://github.com/bazelbuild/bazel/blob/master/site/docs/bazel-overview.md)(CommitID:817e220)
# Bazel概览
Bazel是一款类似于Make, Mave, Gradle的开源构建及测试工具。
Bazel使用了可读性强的高阶构建语言。</br>
Bazel支持多语言，可为多平台构建输出,能够很好的支持大型跨仓库的代码项目以及大量用户。

# Bazel的优势
Bazel带来如下优势：

- **使用高阶构建语言**：Bazel使用一种抽象但易懂的高阶语言来描述工程的构架属性。与其他工具不同的是,Bazel操作的是库, 二进制, 脚本, 数据集等等概念,屏蔽了编译器和链接器的复杂细节。


- **Bazel快速与可靠兼备**：Bazel会缓存所有已经完成的工作,并跟踪文件内容和构建命令的变化，这样一来Bazel能够准确的知道哪些东西是需要重新编译的,并且只编译这些东西。通过搭建高并行和增量的构建可以进一步加速你的构建。

- **Bazel支持多平台**：Bazel可以运行在Linux,MacOs,Windows平台上,通过Bazel可以基于相同项目为PC,服务器，移动设备等多平台构建二进制和软件包。 

- **Bazel能轻松应对大规模项目**： Bazel在编译10万以上文件的编译时依旧能保持敏捷。Bazel能够很好的支持大型跨仓库的代码项目以及大量用户。


- **Bazel极具拓展性**：Bazel支持[多种语言](https://github.com/bazelbuild/bazel/blob/master/site/docs/rules.md),你可以拓展Bazel来支持其他语言或框架。


# 未完待续

