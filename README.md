#第二波更新（1.6版本 7月27日）
  新增：清空按钮
  <img width="959" alt="e8f17264eecc90542bd388766e097eb" src="https://github.com/RexHanG96/Phono-DF-1.0/assets/140506479/5d560295-877c-476b-b446-76c7ff9bbc39">

# 第一波更新来了（1.5版本）
   
   解决了输入框背景色/文字颜色无法更改的问题（是的，我把这部分删了）。

   增加了新的功能：自动保存地址——第一次打开使用的地址会被保存，第二次打开的时候会询问是否添加新的地址，如果选n(否)，会直接按照原先的地址打开界面。
   ![更新](https://github.com/RexHanG96/Phono-DF-1.0/assets/140506479/583f4bee-2c40-47f5-9bae-099b2299e4f5)


# Phono-DF 1.0 

本软件系开源软件，主要用于生成音系区别特征的学习与教学，目前只有windows版本，在win11系统上调试结果为运行稳定。
![界面](https://github.com/RexHanG96/Phono-DF-1.0/assets/140506479/4ddf7719-a11d-4bb6-9777-68061679bc4a)



数据来源：
               https://github.com/PhonologicalCorpusTools/PCT_Fileshare/tree/main/FEATURE
            
背景图片来源：  Pixabay

安装教程：
    
    1. 点击安装（一定要点选在桌面创建快捷方式）
    
    2. 安装成功之后，点击快捷方式
    
    3. 首先出现一个CMD界面，让你输入：解释器的地址（本应用依托python，因此要输入python.exe地址：例如，D:/python/python.exe）
    
    4. 出现主界面（一定不要关闭CMD）


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

# License 

MIT
