本仓库记录学习langchian的一些代码，主要设置为以下三部分

1. langchain基础：基于书籍[<<面向开发者的大模型手册>>](https://github.com/datawhalechina/llm-cookbook)学习的来
2. langchain进阶：在深入思考LLM后，认为llm开发者需要了解llm具备的一些能力
3. 使用langchain构建RAG项目：LLM主流应用方向

**为什么这样设置学习目录呢？** 因为我本人是从CV工程师，需从零学习LLM相关知识，所以我设计的第一部分目的是使用LLM，核心内容是提示词工程prompt，只有了解这个概念，才能进行后续学习；在第二部分，需要了解LLM的使用，这里喝具体的项目无关，就是核心是如何扩展LLM的能力；在第三部分，通过在LLM主流应用方向上实践，进一步掌握langchian


脚本目录：

|序号|基础|进阶|RAG|
|---|---|---|---|
|1|[模型](langchian基础01-模型.ipynb)|[函数调用FunctionCalling](langchian进阶01-函数调用FunctionCalling.ipynb)|[数据加载](lagnchian构建RAG01-数据加载.ipynb)|
|2|[提示词Prompt](langchian基础02-提示词Prompt.ipynb)|[结构化输出StructedOutput](langchian进阶02-结构化输出StructedOutput.ipynb)|[文档分隔](langchian构建RAG02-文档分隔.ipynb)|
|3|[存储](langchian基础03-存储.ipynb)|[代理Agent](langchian进阶03-代理Agent.ipynb)|[向量数据库](langchian构建RAG03-向量数据库.ipynb)|
|4|[模型链](langchian基础04-模型链.ipynb)|[工作流WorkFlow](langchian进阶04-工作流WorkFlow.ipynb)|[生成](langchian构建RAG05-生成.ipynb)|
|5|[模型评估](langchian基础05-模型评估.ipynb)|||
