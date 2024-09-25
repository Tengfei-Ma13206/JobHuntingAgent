# JobHuntingAgent
Use LLM  and Search Engine to find the best suitable jobs and generate CV automatically according to job description. Our aim is to save procrastinators and eventually add a cache system for your life. 

## PRD：
## 1. 整理好自身的经历
- 根据已有的第一份简历，让大模型进行细节询问，丰富简历
## 2. 对经历进行语意分割
## 3. 对分块后的经历进行嵌入（Embedding）
## 4. 根据用户需求提炼出关键词、短语
## 5. 用搜索引擎进行搜索，从返回的链接中解析出，岗位描述和岗位需求
## 6. 将岗位需求和岗位描述也进行语意分割，嵌入（Embedding）
## 7. 计算余弦相似度，取出前N 个相互匹配的“经历-需求”对
## 8. 重排
## 9. 根据最符合的“经历-需求”送给大模型进行简历的撰写
## 10. 根据链接进行自动化投递
