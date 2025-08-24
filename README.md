# 🔍 Extracting Technical Skills from Job Descriptions

## 🧠 Project Overview

This project compares **two different approaches** for extracting technical skills from job descriptions (JDs):

- **Approach 1:** TF-IDF / CountVectorizer / N-gram + WordCloud  
- **Approach 2:** LLM Prompting (ChatGPT)

The goal is to identify **the most frequently requested data-related tools and technologies**, and help job seekers (like myself) prioritize what to learn next.

---

## 🎯 Why I Built This

As a **data analyst job seeker**, I created this project to understand which key technical skills appear most often in job descriptions — especially the ones I **personally lack** — so I can quickly fill in those gaps and land a role I truly want.

I initially tried a traditional **TF-IDF and bigram-based** approach. While helpful, it required **a lot of manual filtering** and still returned many generic or irrelevant results.

To improve this, I implemented **LLM prompting** with ChatGPT to extract structured skill sets with **minimal manual intervention**. This approach revealed truly valuable keywords like:

- `AWS`  
- `Google Cloud`  
- `Snowflake`  
- `dbt`  
- `Power Apps`  
- `Looker`

These were less obvious before, but clearly important in today’s data landscape.
