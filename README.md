信息检索系统

环境：

python3, flask, nltk， gensim

使用：

view.py  执行可视界面

BM25.py   执行检索比赛

使用的方法：

建立了题目，全文的索引表（还可以建的更细致提高检索效果与精度）

使用BM25模型，添加了部分权重

使用NLTK.wordnet, 以及数据集训练得到的词向量作查询扩展（效果都不好，可以使用医学NCI的词库）

未实现查询反馈

百度云里的倒排索引表要放到根目录下！