# Project: LangChain SQL Database Interaction
![image](https://github.com/user-attachments/assets/bba30714-9131-4531-9eb4-12ccb68a56c2)

Notebook: langchain_sql.ipynb

This project demonstrates how to use LangChain to interact with an SQL database. It involves querying a sample SQLite database to retrieve and analyze information.

Key Components:

AzureChatOpenAI: Leverages Azure's OpenAI API for natural language processing.

SQLDatabase: Connects to and interacts with an SQLite database.

create_sql_agent: Builds an agent that can execute SQL queries and process the results.

Example Output:

Question: List the total sales per country. Which country's customers spent the most?

Agent Execution:

Entering new SQL Agent Executor chain...

Final Answer: The country with the highest customer spending is the USA, with a total sales amount of $523.06.
Finished chain.
