# LangChainExample
基于https://github.com/liaokongVFX/LangChain-Chinese-Getting-Started-Guide
代码做的基于langchain最新库的代码 
把每个例子的输出都放入了 output_result 文件夹
主要区别如下
1. 从 from langchain.llms import OpenAI 改为 from langchain.chat_models import ChatOpenAI
2. 从 from langchain import SQLDatabaseChain 改为 from langchain_experimental.sql import SQLDatabaseChain
