# customer-support-ai

Fine-tuned customer support AI using Adaption AutoScientist

\# Customer Support AI Assistant 🤖



A fine-tuned AI model for handling customer support queries using Adaption's AutoScientist.



\## 📊 Project Details



\- \*\*Model Name:\*\* Customer Support AI

\- \*\*Base Model:\*\* Qwen3.5 4B

\- \*\*Training Method:\*\* LoRA (Low-Rank Adaptation)

\- \*\*Dataset Size:\*\* 1,093 customer support conversations

\- \*\*Performance:\*\* 50.92% win rate

\- \*\*Status:\*\* ✅ Deployed and Live



\## 🚀 Model Deployment



\*\*Model ID:\*\* `stack/customer-support-ai`

\*\*Stack ID:\*\* `ba60ecf2-abc7-4cd8-ba82-17d3e78a233e`



\## 📝 How It Works



1\. \*\*Data Collection:\*\* Gathered 500 customer support samples

2\. \*\*Data Adaptation:\*\* Used Adaption's Adaptive Data to expand to 1,093 rows

3\. \*\*Model Training:\*\* Fine-tuned using AutoScientist with 3 optimization iterations

4\. \*\*Deployment:\*\* Deployed as a live API stack on Adaption



\## 💡 How to Use



\### Via Adaption API:

```python

import requests



\# Call your deployed model

model\_id = "stack/customer-support-ai"

query = "How do I reset my password?"



\# Make API request to Adaption

response = requests.post(

&#x20;   "https://api.adaption.ai/responses",

&#x20;   json={

&#x20;       "model": model\_id,

&#x20;       "messages": \[{"role": "user", "content": query}]

&#x20;   }

)



print(response.json())

🛠️ Technologies Used



Adaption Platform - Data adaptation and AutoScientist training

Qwen3.5 4B - Base language model

LoRA - Efficient fine-tuning technique

Python - Integration and testing



📈 Training Results



Iterations: 3/3 completed

Best Win Rate: 50.92%

Learning Rate: 0.00018

LoRA Rank: 32

Epochs: 3



🎯 Use Cases



Customer support chatbot

FAQ automation

Help desk automation

Customer inquiry handling



📞 Support



For questions about the model or deployment, refer to Adaption documentation.



\---



Created with Adaption AutoScientist ✨

