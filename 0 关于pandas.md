[PDF版本](http://pandas.pydata.org/pandas-docs/stable/pandas.pdf)

[HTML压缩版本](http://pandas.pydata.org/pandas-docs/stable/pandas.zip)

时间: May 16, 2018 | 版本: 0.23.0

二进制安装程序：https://pypi.org/project/pandas

源码库：http://github.com/pandas-dev/pandas

讨论区：https://github.com/pandas-dev/pandas/issues

Q&A支持：http://stackoverflow.com/questions/tagged/pandas

开发组邮件列表：http://groups.google.com/group/pydata

**pandas**是一个Python包，它提供了快速、灵活、有表现力的数据结构。设计这些数据结构的目的，是为了更加简单、更加符合直觉地操作**相互关联的**或**带有标签属性**的数据。pandas的目标是成为Python分析实用的、现实世界产生的数据的基本高级构成要素。另外，pandas还有更广阔的目标：成为**所有语言最有力、最方便的数据操作和分析工具**。现在，pandas已经很好地走在奔向这个目标的路上。

pandas适合处理多种类型的数据：
- 表格数据，每列表示不同的类。例如SQL表格或者Excel表格。
- 排序的或未排序的时间序列数据。
- 行和列各有含义的矩阵数据。
- 其他形式的观测数据集或统计数据集。数据放入pandas数据结构时不必带有标签。

pandas特有的两个数据结构，`Series`和`DataFrame`，可以应对大部分金融、统计、社会科学和很多工程领域的典型使用场景。对于R用户来说，`DataFrame`在提供了R的`data.frame`提供的所有特性之外，还提供了更多的特性。pandas构建在[Numpy](http://www.numpy.org/)之上，目的是在科学计算环境中更好地集成第三方库。

Pandas表现的比较好的方面：
- 轻松处理浮点型**缺失数据**（用NaN表示）和非浮点型缺失数据。
- 数据大小可变：DataFrame和更高维的对象的列可以**插入和删除**。
- 自动地、清晰地**数据规整**：数据对象会被自动地规整到一组标签集，或者，使用者可以简单地忽略标签，在计算时，让Series和DataFrame自动规整数据。
- 强大而灵活的**分组**方法，在数据聚合和转换中，更好地对数据集进行分割、应用和组合。
- 更容易地将粗糙的、带有不同索引的Python和Numpy数据**转换**成DataFrame。
- 基于标签的**切片、索引和子集构造**。
- 基于直觉的**数据连接（merge和join操作）**。
- 方便的**数据变形（reshape和pivot操作）**。
- **多级**轴标签（每个标记可能有多个轴标签）。
- 强壮的用来加载**Flat文件**（csv或逗号分割的文件）、Excel文件、数据库文件的IO工具，超快的**HDF5**格式数据的加载和保存。
- 处理**时间序列**的特殊功能：日期范围生成和频率转换，移动窗口统计，移动窗口线性回归，日期移位和滞后等等。

pandas的许多设计原则都是为了解决在使用其他语言时或在科学研究中常见的问题。数据科学家的工作一般分为三部分：改写和清理数据、分析建模、组织结果呈现。pandas是这些工作的理想工具。

pandas其他的特点:
- pandas很快。在[Cython](http://cython.org/)代码中，许多底层算法被广泛地调整过。但是，就像其他任何东西一样，泛化通常会牺牲性能。所以，如果你关注你的应用程序的一个特性，你可以创建更快的专门工具。
- pandas依赖[statsmodels](http://www.statsmodels.org/stable/index.html)，也因为此，pandas在Python统计计算生态系统中占有重要的位置。
- pandas被广泛地应用在金融领域。

注：本文档默认读者对Numpy有大致的了解。如果你没有使用过Numpy，请移步：[learning about Numpy](https://docs.scipy.org/doc/)。







