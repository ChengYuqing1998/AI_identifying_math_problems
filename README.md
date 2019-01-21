# AI智能识题
## 简介：
根据提供的试题数据信息，利用这些有标签的数据对文字进行建模，产生一个模型能对试题进行打标签处理，确定这个试题属于哪一类的试题。利用题库数据, 使用TF-IDF方法将每一道题目用一个向量表示，然后选择模型如贝叶斯，k近邻，随机森林等，对“三角函数与解三角函数” 和“函数与导数”的题目进行分类，并在最终的代码和相关的结果记录在报告中。
## 数据集文件：
	
  knowledge_hierarchy.csv：知识体系表格，记录了知识体系之间的上下层级关系和知识体系的基本信息;
	
  question_knowledge_hierarchy_sx.csv：高中数学试题与知识体系对应表;
	
  tk_answer_option_sx.csv：题目选项表格，记录了题目选项的所属试题、内容、被创建和被修改的信息等;
	
  tk_question_sx.csv：试题信息表格，记录了题干自身属性、状态、被创建修改审核信息。
## 编码方式：
utf-8
## 使用语言及工具：
Python 3.6 ，Jupyter Notebook
## 使用工具包：

numpy ; pandas ; matplotlib.pyplot ; re ; mlxtend.classifier ; jieba ;

sklearn:
1.	sklearn.neighbors,
2.	sklearn.naive_bayes,
3.	sklearn.ensemble, 
4.	sklearn.linear_model,
5.	sklearn.svm,
6.	sklearn.metrics,
7.	sklearn.cross_validation, 
8.	sklearn.feature_extraction.text, 
9.	sklearn.pipeline,sklearn.grid_search

