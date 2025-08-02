<div align="center">
  <img src="https://github.com/user-attachments/assets/309a716f-2361-40fe-af09-6829149e5f1b" alt="Sentiment Plot" width="400"/>
</div>

# 🇺🇸 US Election Sentiment Analysis using Twitter Data 🗳️

This project analyzes public sentiment from Twitter around the 2020 US Presidential Election between **Donald Trump** and **Joe Biden**, using Natural Language Processing (NLP). The aim is to extract, quantify, and visualize voter sentiment trends, engagement, and momentum leading up to election day.

---

## 📌 Project Highlights

- Performed sentiment analysis on thousands of tweets related to the US Election.
- Compared **positive, negative**, and **neutral** sentiment across both major candidates.
- Analyzed engagement metrics like **likes per tweet**, **total interactions**, and **momentum shifts**.
- Compared sentiment-derived predictions with actual election outcomes at the **state level**.

---

## 📊 Key Insights

- **Trump** received **54.4% positive sentiment**, suggesting a highly **engaged and vocal support base**.
- **Biden** had **45.6% positive sentiment**, but his sentiment trend showed **more stability** with fewer sharp declines.
- **Weighted sentiment** (factoring tweet volume and engagement) leaned toward **Biden at 50.9%**, with **Trump at 49.1%**, **closely matching the actual election result**.
- **28 out of 50 states** were correctly aligned with the actual election trend using sentiment prediction.
- **40–50% of negative sentiment** toward one candidate likely reflected **support for the other**, indicating patterns of **protest voting**.

- <img width="1200" height="1200" alt="image" src="https://github.com/user-attachments/assets/3ba3fed3-971c-4820-88ed-ddc5b409d420" />


---

## ❓ What is Protest Voting?

> **Protest voting** occurs when voters **cast their vote not to support a preferred candidate, but to oppose another**.  
> In this analysis, negative sentiment toward one candidate often corresponded with a rise in positive sentiment for the opponent — indicating indirect voter preferences.
>
> <img width="980" height="484" alt="image" src="https://github.com/user-attachments/assets/14946299-1c98-4db0-9109-c8f073515e67" />


---

##  Engagement Metrics

- **Trump’s tweets** received higher **total interactions** overall, reflecting his strong online presence.
- **Biden** had **higher average engagement**:  
  - **10.58 likes per tweet** vs. **Trump’s 7.41 likes per tweet**
- **Biden gained more consistent momentum** closer to election day, especially in swing states.

---

## 📈 Visualizations

- ✅ **Sentiment Distribution Plots** (Positive/Negative/Neutral)
- ✅ **State-wise Sentiment vs Actual Results**
- ✅ **Word Clouds** of most frequently used political terms
- ✅ **Time-Series Sentiment Plots** tracking candidate momentum
- ✅ **Engagement Bar Graphs** (likes per tweet, total tweet volume)

> 📎 Kaggle Dataset Source: [US Election Sentiment Analysis on Kaggle](https://www.kaggle.com/code/farheenshaukat/nlp-sentiment-analysis-for-us-election/input)

---

## 🛠️ Tools & Technologies Used

- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Plotly)
- **NLP Libraries**: TextBlob, VADER, NLTK
- **Twitter API / CSV Dataset**
- **Jupyter Notebook / Google Colab**
- **Scikit-learn** for classification and model evaluation

---

## ✅ Outcomes

- Modeled real-world political sentiment through unstructured text data.
- Understood behavioral patterns like protest voting.
- Matched prediction results with real election outcomes.
- Gained insights into how social media engagement shapes public perception.

---
