# ReqDeDup

The project is intended to design a requirement dedup tool, based on embedding and LLM. Please refer to the following wiki page for details:
	[基于大模型的需求自动去重工具](https://avb8u30devt.feishu.cn/wiki/Vy9EwKXNZi5D6WkzMZDcyKKUnCe)
	p.s. I will do the translation later

The code is written in Jupyter Notebook:

STEP 1: Utility functions to prepare the requirement data file
	get-redmine-req-data.ipynb
STEP 2: Calc cosine similarity, and form the prompt files
	req-dedup.ipynb
STEP 3: Use TongYi batch to judge the duplication
	batch_try.ipynb
STEP 4: Result analysis - Calculate precission, recall and accuracy
	calc_recall_and_precission.ipynb

The project also contains a lot of other files, including both input and output files. But you can skip STEP 1 if you are not so interested in how to retrieve the requirement dataset from redmine. If so, you can just start with STEP 2, and the input file "all_issues_for_test.csv", which contains 743 requirements. 


