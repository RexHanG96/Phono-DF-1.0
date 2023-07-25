# Phono-DF 1.0 

本软件系开源软件，主要用于生成音系区别特征的学习与教学，目前只有windows版本，在win11系统上运行稳定。


当前数据来源：
            https://github.com/PhonologicalCorpusTools/PCT_Fileshare/tree/main/FEATURE


安装教程：
    1. 点击安装（一定要点选在桌面创建快捷方式）
    2. 安装成功之后，点击快捷方式
    3. 首先出现一个CMD界面，让你输入：解释器的地址（本应用依托python，因此要输入python.exe地址）
    4. 出现主界面（不要关闭CMD）


使用教程：
   * 基本结构：左侧：有输入栏，下方两个按钮；中间为输出栏；右侧为音段列表；上方为系统选择菜单和基本属性设置菜单。
   * 左侧：
        * 输入栏：支持输入多个IPA符号，用英文逗号隔开
        * 区别特征抽取：根据用户输入的IPA符号，输出其区别特征的集合（显示在左输出栏）
        * 提取共同特征：根据左侧输出栏输出的特征（至少两个，否则会报错），提取两者（或者多个音段）的区别特征的交集，
        * 并列出减去交集后各个音段的区别特征集合中剩下的元素的集合。（显示在右输出栏）
   * 右侧：
        * 音段列表：不同的系统略有差异，基本功能一致，点选音段，在右输出栏输出选中音段的区别特征集和。
   * 上方：系统选择菜单：目前只有SPE系统和Hayes(2009)的系统，
        * 后续或许会添加其他的系统（取决于我忙不忙）。
        * 基本属性菜单：我就不多说了，这个很简单，自己摸索一下就行。

  
  写在最后：如果有意见建议，欢迎来信：1643511915@qq.com

#License 

MIT
