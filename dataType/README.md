请在index.html文件中，编写arraysSimilar函数，实现判断传入的两个数组是否相似。具体需求：  
1. 数组中的成员类型相同，顺序可以不同。例如[1, true] 与 [false, 2]是相似的。  
2. 数组的长度一致。  
3. 类型的判断范围，需要区分:String, Boolean, Number, undefined, null, 函数，日期, window.  
当以上全部满足，则返回"判定结果:通过"，否则返回"判定结果:不通过"。  