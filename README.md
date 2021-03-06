标注规则
======
    文件夹包含若干文件，每个文件以名称划分了初分的裁判结果。标注的目的是阅读每个文件的内容，将明显属于其他分类的应该将其剪切到应该属于的分类下，不知道怎么分类的数据可以删除。
    如:
        在“other”下发现“驳回上诉，维持原判”，将其剪切至“驳回上诉维持原判”文件内。
```diff
    -重点查看other中的内容，此项内容中的数据可能有较多应当属于其他分类
```
    注：other文件是明显不属于如下19项的句子，以下19项是与判决相关的项目，而other则是文书固定套话或者是对判决的解释。
    注2：剪切的过程中只要保证一行只有一句话，可以打乱原有顺序，在任意两行之间粘贴。
    注3：发还这个虽然时常和退赔同时出现，但并不能认为发还∈退赔。 
    注4：编辑文档可以使用sublime text、Atom等工具，在File->open folder 可以以树状结构直接打开文件夹，点开树中的子节点就可以直接打开文件。其他可以打开文件夹的工具都较为方面使用。
    注5：带并罚的，并罚前是解释，并罚后是判决：“与前罪未执行的管制三个月、并处罚金人民币二千元并罚”这种属于对判决的解释，应放入other。此句原句应为“...并罚，判处管制XX月，罚金XX”。
    注6：“一、被告人刘鲁健犯盗窃罪，判处有期徒刑十二年，剥夺政治权利二年，并处没收财产人民币三万元”这种因为分句错误导致一句话若干意思的可以直接删除
    
# 刑罚
## 1. 定罪
    例如被告人XXX犯盗窃罪
## 2. 有期徒刑
    刑期至XXXX年XX月XX日不算是有期徒刑，如果遇到需要将其剪切至other文件
## 3. 缓刑
## 4. 拘役
## 5. 管制
## 6. 假释
    准许假释和不予假释都属于假释
    “撤销上海市第一中级人民法院对被告人袁某假释考验期限自2013年7月10日起至2015年3月31日止的刑事裁定书”这种应该为撤销前审判决
    “假释考验期自2014年1月23日起至2015年2月28日止” 应该为other
## 7. 剥夺政治权利

# 经济处罚
## 8. 罚金
    罚金在本判决生效后一个月内缴纳 属于other
## 9. 退赔
## 10. 没收作案工具及赃款赃物
## 11. 扣押
## 12. 收缴
## 13. 追缴所得
    追缴作案所得多少多少
    注：追缴所得并退赔被害人的算退赔
    
# 裁定
## 14. 减刑
    减刑后，刑期至XXXX不算减刑，如果遇到需要将其剪切至other文件
    同理，“减刑后刑满释放期为2016年10月5日”应该为other
## 15. 不予减刑
## 16. 准许撤回上诉
## 17. 准许撤回起诉
## 18. 驳回上诉，维持原判
## 19. 撤销前审判决
    撤销部分前审处罚也算撤销前审判决，只标注那一句
    如：
    撤销刑罚    ->  撤销前审判决
    罚金4088不变    ->  罚金
## 20. other
    other文件是明显不属于上述19项的句子，上述19项是与判决相关的项目，而other则是文书固定套话或者是对判决的解释。
    但是有可能粗分的时候某些特殊写法会被分入other，此时需要剪切此句到其他文件。
    如：
    判决其有期徒刑XX年         需要将这个剪切到有期徒刑中
