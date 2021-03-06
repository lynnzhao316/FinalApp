# 第四部分 作品实现、特色和难点

## 4.1 作品实现

这款App完美实现了在移动端对留学申请项目信息的录入和显示，能够以缩略信息和详细信息两种模式显示每个项目的信息，并支持录入后再次编辑的功能。简洁明了，方便实用，弥补了现有记事软件没有专门功能的缺憾。

## 4.2 特色分析

这款App最主要的特色是结合了大量出国留学同学的经验，对留学项目信息的录入做了专门化的处理，简化了使用通常的记事软件记录相应内容的步骤，方便了有需求人群的使用。

## 4.3 难点和解决方案

难点一：AppInventor不支持组件的动态添加

由于开发工具不支持组件的动态添加，因此对不断增加条目的记事类软件构成了不可逾越的障碍。鉴于这款App具有针对性，一般情况下添加的条目不超过20个，因此在开发时手动设置了20个可以显示信息的条目栏以解决这一问题。

难点二：微数据库不支持初始内容的设置

微数据库的相应操作必须至少在程序第一次启动之后进行，而不支持在程序启动前内置信息。因此程序启动时不能从1开始读取编号，必须设置在读不到数据的情况下的相应操作，显得繁琐。

难点三：AppInventor不支持变量的批量命名处理

与其不支持组件的动态添加的缺点相对应，AppInventor同样不支持变量的批量命名和处理。这就使得对于第一个屏幕上的每一个条目都需要设置相似的过程用于读取数据。过程除了各处理对象不一样外其他的都一样。这只有通过为每一个条目编写读取的程序来解决。

难点四：AppInventor支持的颜色种类太少

AppInventor对颜色的支持过于少，使得设计具有鲜明风格的UI变得不太可能。这一问题一定程度上可以通过添加图片背景的方法解决。




