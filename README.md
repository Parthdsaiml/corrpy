# 🧠 CorrPY – Correlation Made Easy

![PyPI version](https://img.shields.io/pypi/v/corrpy)
![Downloads](https://img.shields.io/pypi/dm/corrpy)
![License](https://img.shields.io/pypi/l/corrpy)
![Python](https://img.shields.io/pypi/pyversions/corrpy)

---

**CorrPY** is your lightweight buddy for fast, smart correlation analysis.  
Forget just numbers — CorrPY tells you **what they *mean***. 📊✨

Built for data scientists who want **insights**, not just values.

---

## 🚀 Install

```bash
pip install corrpy
```

---

## 📦 Quickstart

```python
from corrpy import Corrpy

corrpy = Corrpy()
corrpy.getTotalCorrRelation(df)
```

✅ Analyze correlation across features  
✅ Get trends + easy-to-read interpretations  
✅ Go deeper with AI explanations (optional)

---

## 🔥 Key Features

- **Numerical vs Numerical** — Classic correlations + strength.
- **Object vs Numerical** — Category impacts, clear trends.
- **Object vs Object** — Categorical association (Chi2).
- **Transitive Trap Alerts** — Detect hidden indirect links. 🚨
- **AI-Generated Insights** — Explain data like a boss 🧠📜

---

### Methods

1. `getTotalCorrRelation(df, features = ["Correlation", "Pearson", "Distance"], feature = "Correlation", short = False)`: Pass a pandas DataFrame to get correlation analysis across all columns and get trends, interpretations and score with respect to feature u added in parameter.
2. `getGroupInf(objColumn, numColumn, df)`: Compute the correlation between the given object column and the given numeric column.
3. `getAllGroupInf(df)`: Compute the correlation between all object columns and all numeric columns.
4. `setApi()`: Securely handles your [Together.ai](https://www.together.ai/) API token.
5. `checkTransit(firstFeature, secondFeature, ThirdFeature)`: Check for transitive correlation between three features.
6. `checkTransitForColumn(column, df)`: Check for transitive correlation between a column and all other columns.


### AI-Generated Insights

1. `explainAITC(df, feature="Correlation", character="Data analyst", mode="Confused")`: Get AI insights for correlation analysis.
2. `explainShift(num1, num2, shiftValue, df, character = "Data analyst", mode = "Funny...", prompt = "Explain like a stand-up comedian")`: An AI analyst explains the output of `shift()` like you're in a meeting with your CEO.
3. `explainPartialCorrelation(num1, num2, df, character = "Data analyst", mode = "Funny...", prompt = "Explain like Angry Professor")`: Get AI insights for partial correlation analysis.
4. `explainTransitForcolumn(column, df, character = "Data analyst", mode = "Funny...", prompt = "Explain like Oppenheimer")`: An AI analyst explains the output of `checkTransitForColumn()` like you're in a meeting with your CEO.
5. `explainAI(result, character = "Data analyst", mode = "Funny...", prompt = "Explain like angry professor")`: Get AI insights for any result.
6. `makeReport(self, method="null", df=None, column=None, feature=None, target=None, prompt="Null", size="short", constant=None, first=None, second=None, third=None)`: Generate a human-like, well-written paragraph suitable for direct pasting into a PowerPoint slide, based on the output of other methods.
---


## 👤 Available Characters

- Data Analyst  
- Manager  
- Data Scientist  
- Data Engineer  
- Modi  
- Elon Musk  
- Angry Professor  
- Chandler Bing  
- Stand-up comedian
- Oppenheimer
- Mahatma gandhi


(*More being added weekly – you can easily expand the template!*)

---

## 🎭 Emotion Modes (aka `mode`)

- Happy 🎉  
- Angry 😠  
- Sad 😢  
- Excited 🤩  
- Confused 😕  
- Serious 💼  
- Sarcastic 🙃  
- Romantic 💘  
- Zen 🧘  
- Paranoid 🕵️
- Overwhelmed 😩
- Curious 🤔
- Cautious ⚠️
- Funny 😂




---





## 🧠 Example Insights

> *"Age and Fare have a moderate positive correlation.  
Pclass has a strong inverse relation with Fare."*

✨ Plus visual trends, interpretation tags, and more!

---

## 👨‍💻 Author

**YellowForest**  
🔗 [GitHub](https://github.com/Parthdsaiml)

---

## 📄 License

BSD 3-Clause License

---

# ⚡ TL;DR

| # | What CorrPY Gives You |
|:-|:--|
| 🚀 | Quick, meaningful correlation analysis |
| 🤖 | AI-driven explanations |
| 🧩 | Find hidden patterns |
| 🔥 | Detect transitive traps |
| 🎯 | Ideal for both beginners and pros |

---

# 📢 FINAL NOTE:

> **CorrPY isn't just another EDA tool...  
> It's your data's best storyteller. 📚🚀**

---

# 🧹 How to use:
- README for Quick Start 📑
- Full GUIDE.md for Deep Dive 📚
