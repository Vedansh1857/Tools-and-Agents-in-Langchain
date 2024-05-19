# Tools-and-Agents-in-Langchain

### 1. From Langchain tools imported both WikipediaQueryRun & ArxivQueryRun.
### 2. Used api wrappers(WikipediaAPIWrapper & ArxivAPIWrapper respectively) present in langchain utilities for both.
### 3. Hence, created 2 tools --> Wiki & arxiv.
### 4. Apart from these two, I created my own custom tool("langsmith-search").
### 5. For any questions regarding LangSmith, we must use this tool.
### 6. While for any query regarding any research paper, one must use arxiv tool.
### 7. And for any other random query, one must use wiki tool.
### 8. Finally, stored all these 3 tools in a list & create an agent to execute those tools.
### 9. For any query, the agent will automatically detect which tool to use to answer the query.
