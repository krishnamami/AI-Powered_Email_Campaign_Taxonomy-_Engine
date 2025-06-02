# AI-Powered_Email_Campaign_Taxonomy-_Engine

Automatically classify and extract taxonomy attributes from email campaigns using OpenAI's language models, FAISS for rule retrieval, and LangChain for orchestrating the logic.
## 🚀 Project Overview

This project demonstrates how to:
- Encode plain-text business rules for taxonomy extraction.
- Retrieve the most relevant rule using vector similarity (FAISS).
- Use LLMs (via OpenAI) to generate structured taxonomy.
- Validate taxonomy output using Pydantic.
- Save results as a CSV for downstream use.

Great for automating **email marketing workflows** where taxonomy consistency is critical.

![image](https://github.com/user-attachments/assets/a574f56e-31df-4760-a9f1-21658c215bda)


---
Required packages include:

.openai
.langchain
.faiss-cpu
.pydantic
.pandas
.streamlit
.streamlit pyngrok --quiet


📁 

├── App.py               # Main script

├── requirements.txt      # Python package dependencies


💡 How It Works
1.Define Rules
Embed plain-text taxonomy rules using OpenAI embeddings.

2.Retrieve Rule
Use FAISS to find the most relevant rule based on source ID (e.g., sfmc_347_august).

3.Generate JSON
Prompt an LLM to convert rule into structured JSON.

4.Validate JSON
Use Pydantic to validate the fields.

5.Output Result
Extract template_id and offer_type from input metadata and write to CSV.

📈 Use Cases

-Automating taxonomy tagging for email retention campaigns

-Powering downstream tools like Salesforce, SFMC, or Klaviyo

-Enabling data pipelines for email performance analysis

-Reducing human error in manual classification processes


## Related Projects
[Fine_Tuning_LLM](https://github.com/krishnamami/Fine_Tuning_LLM)

[Multi Agent Anamoly Detection](https://github.com/krishnamami/Multi_Agent_Anamoly_Detection)

✍️ Author
Krishna Goud

Head of Data Engineering & MLOps | Rocket LA  [LinkedIn](https://www.linkedin.com/in/krishnagoud)

