
# 🏢 Company Analysis: Named Entity Recognition and Topic Modeling

This project analyzes tweets and news articles about a specific company to identify:
- **Frequently mentioned companies and locations**
- **Most discussed topics in media and social platforms**

The project was developed as part of the University of Chicago's Applied Data Science program.  
It is designed so **both technical and non-technical readers** can quickly understand and interact with the results.

---

## 📌 Project Goals
1. **Identify key entities** — such as companies and locations — mentioned alongside the target company.
2. **Discover trending topics** from tweets and news articles.
3. **Visualize findings** to help business stakeholders gain quick and actionable insights.

This analysis can help companies monitor public perception, identify emerging trends, and respond to reputational risks in real time.

---

## 📊 Key Insights at a Glance

### 1) Top 20 Companies — News
These are the companies most frequently mentioned in **news articles** alongside the target company.  
![Top Companies in News](images/Company_Entity_Analysis_1.png)

### 2) Top 20 Companies — Tweets
These are the companies most frequently mentioned in **tweets** about the target company.  
![Top Companies in Tweets](images/Company_Entity_Analysis_2.png)

### 3) Top 20 Locations — News
Top **geographic locations** linked to the target company in news articles.  
![Top Locations in News](images/Company_Entity_Analysis_3.png)

### 4) Top 20 Locations — Tweets
Top **geographic locations** linked to the target company in tweets.  
![Top Locations in Tweets](images/Company_Entity_Analysis_4.png)

### 5) 🧩 Topic Modeling Results (Top 5 Topics)
Recurring themes extracted using **LDA topic modeling** from both tweets and news.  
The optimal number of topics was selected based on the coherence score, which evaluates how semantically meaningful and distinct the topics are.

The five discussion themes include:

- **Software and Corporate Achievements**  
  *Keywords:* microsoft, ever, number, window, year, own, word, use, know, activision

- **Microsoft in the Tech Ecosystem**  
  *Keywords:* microsoft, ceo, premium, netflix, grammarly, apple, canva, spotify, account, quillbot

- **Products and Services**  
  *Keywords:* microsoft, use, new, excel, know, work, business, today, learn, xbox

- **Community and Engagement**  
  *Keywords:* microsoft, amp, get, one, power, time, team, like, free, take

- **Gaming Industry**  
  *Keywords:* microsoft, game, buy, xbox, sony, billion, like, google, company, activision

![Topic Modeling](images/Company_Topic_Modeling_Analysis_1.png)

---

## 🔍 How It Works (Non-Technical Overview)

1. **Data Collection** — Gathered tweets and news articles about the company.
2. **Text Cleaning** — Removed non-English and irrelevant text.
3. **Entity Recognition** — Used NLP to identify companies and locations.
4. **Topic Modeling** — Applied LDA to extract discussion topics.
5. **Visualization** — Created charts and HTML reports for easy interpretation.

<p align="center">
  <img src="images/Company_Entity_Analysis_1.png" width="500"><br>
  <em>Example output from Named Entity Recognition</em>
</p>

---

## 🧠 Why This Matters
- **Named Entity Recognition (NER)** reveals **who** and **where** is frequently associated with the company.
- **Topic Modeling** uncovers **what** people are talking about.
- This approach enables companies to **monitor brand reputation**, **identify trends**, and **spot emerging issues early**.

---

## 📂 Repository Structure

```plaintext
.
├── notebooks/
│   ├── Company Analysis_Starter1.ipynb       # Part A: Named Entity Recognition
│   └── Company Analysis_Starter2.ipynb       # Part B: Topic Modeling
├── images/                                   # Extracted charts and figures
├── requirements.txt                          # Python dependencies
└── README.md                                 # Project description (this file)
```

---

## 🚀 How to View or Reproduce Results

### For Non-Technical Readers
Simply open the HTML files in your browser (if available) to explore the analysis:

- `Company_Entity_Analysis.html`
- `Company_Topic_Modeling_Analysis.html`

> 📎 **Note**: These files may be excluded from the repo due to file size or version control constraints.

---

### For Technical Readers
To reproduce the full analysis:

1. **Clone this repository**
   ```bash
   git clone https://github.com/edwnhsu/Company-Analysis-Named-Entity-Recognition-and-Topic-Modeling.git
   cd Company-Analysis-Named-Entity-Recognition-and-Topic-Modeling
   ```

2. **Create a Python virtual environment (optional but recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate  # Mac/Linux
   venv\Scripts\activate   # Windows
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

5. **Open Notebooks**
   - Run `notebooks/Company Analysis_Starter1.ipynb` for Named Entity Recognition
   - Run `notebooks/Company Analysis_Starter2.ipynb` for Topic Modeling

6. **Outputs**
   - Results will be saved as `.html` files in the root directory.
   - Charts will be saved under `images/`.

---

## 🌟 Credits
This project was completed as part of the **University of Chicago Applied Data Science** program.  
Special thanks to instructors and peers who provided feedback throughout the development.

---

## 📬 Contact
For questions or collaboration:
**Yu-Wei (Edwin) Hsu**  
📫 GitHub: [@edwnhsu](https://github.com/edwnhsu)  
📧 Email: edwinhsu@uchicago.edu
