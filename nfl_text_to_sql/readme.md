# 🏈 NFL Text-to-SQL Assistant

This module enables **natural language questions** to be translated into **SQL queries** that run against a structured NFL statistics database (SQLite). It is part of the larger [FlyGPT](https://github.com/yourusername/FlyGPT) project — a hybrid assistant for Philadelphia Eagles analysis.

---

## 🎯 Goal

Allow users to ask football questions like:

> "How many touchdowns did Jalen Hurts have in 2023?"

And return answers by:

1. Extracting intent and entities  
2. Selecting the right table  
3. Generating an accurate SQL query via LLM  
4. Executing the SQL on local data  
5. Reflecting on result quality and regenerating if needed  

---

