# Text-Editor-UCSD
###### cooperate with UC San Diego Intermediate Software Development MOOC team

一个功能丰富的文本编辑器
* 加载外部文本
* Flesch–Kincaid 易读性测试
* 编辑距离
* 生成Markov 文本
* 拼写检查
* 自动补全
* ...

### Flesch–Kincaid 易读性测试
![alt text](https://github.com/Arthur-Lanc/Text-Editor-UCSD/blob/master/Flesch–Kincaid.png)
左下角的数值为Flesch index值，数值越小，阅读要求越高。可参考下表。

Score | School level | Notes
------------ | ------------- | -------------
100.00-90.00 |	5th grade |	Very easy to read. Easily understood by an average 11-year-old student.
90.0–80.0 |	6th grade |	Easy to read. Conversational English for consumers.
80.0–70.0 |	7th grade |	Fairly easy to read.
70.0–60.0 |	8th & 9th | grade	Plain English. Easily understood by 13- to 15-year-old students.
60.0–50.0 |	10th to 12th grade |	Fairly difficult to read.
50.0–30.0 |	College |	Difficult to read.
30.0–0.0 |	College graduate |	Very difficult to read. Best understood by university graduates.

### 编辑距离
动态生成叶子为单词的树进行广度优先搜索，寻找两单词之间的路径。
![alt text](https://github.com/Arthur-Lanc/Text-Editor-UCSD/blob/master/wordpath.png)

### 生成Markov 文本
生成马尔科夫文本，模仿原作者的风格。
![alt text](https://github.com/Arthur-Lanc/Text-Editor-UCSD/blob/master/genmarkovtxt.png)

### 拼写检查与自动补全
![alt text](https://github.com/Arthur-Lanc/Text-Editor-UCSD/blob/master/spellingsuggest.png)
![alt text](https://github.com/Arthur-Lanc/Text-Editor-UCSD/blob/master/autocomplete.png)

:rocket:
