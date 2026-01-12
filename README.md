
<h1 align="center">Hi 👋, I'm RISHIKANT TIWARY </h1>

<!-- ===================== WORD-BY-WORD ANIMATION ===================== -->
<p align="center">
  <span id="animatedIntro">Aspiring Data Analyst/Scientist • Machine Learning & AI Enthusiast • FastAPI | Docker | Python • Turning Data into Intelligent Systems</span>
</p>

<style>
  #animatedIntro {
    display: inline-block;
    font-size: 1.2rem;
    font-weight: 500;
    color: #4AA3FF;
    line-height: 2;
  }
  #animatedIntro span {
    opacity: 0;
    display: inline-block;
    transform: translateY(20px);
    transition: all 0.4s ease;
    margin-right: 5px;
  }
  #animatedIntro span.show {
    opacity: 1;
    transform: translateY(0);
  }
</style>

<script>
  const introEl = document.getElementById('animatedIntro');
  const words = introEl.textContent.split(' ');
  introEl.textContent = '';
  
  words.forEach(word => {
    const span = document.createElement('span');
    span.textContent = word;
    introEl.appendChild(span);
  });

  const spans = introEl.querySelectorAll('span');
  let delay = 0;
  spans.forEach(span => {
    setTimeout(() => {
      span.classList.add('show');
    }, delay);
    delay += 250; // 250ms between words, adjust as needed
  });
</script>

<!-- ===================== BADGES ===================== -->
<p align="center">
  <a href="https://www.linkedin.com/in/rktiwary1208/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=flat&logo=linkedin">
  </a>
  <a href="mailto:rktiwary1208@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-red?style=flat&logo=gmail&logoColor=white">
  </a>
  <img src="https://img.shields.io/badge/Open%20to%20Work-success?style=flat">
  <img src="https://komarev.com/ghpvc/?username=Hrishiyash&label=Profile%20views&color=0e75b6&style=flat" />
</p>

---

## 👨‍💻 About Me

I am an **Aspiring Data Scientist** with a strong foundation in analytics and business intelligence, currently transitioning toward **Machine Learning, Artificial Intelligence, and backend deployment**.

I enjoy building end-to-end systems — from data preprocessing and analysis to ML models and API deployment.

---

## 🧠 Current Learning Focus

- Machine Learning & AI  
- FastAPI for ML model deployment  
- Docker & MLOps fundamentals  
- Feature engineering & model evaluation  

---

## 🛠 Tech Stack

**Data Science & ML**  
Python · Pandas · NumPy · Matplotlib · Scikit-learn  

**Backend & Deployment**  
FastAPI · Docker  

**Data & Analytics**  
SQL (MySQL) · Power BI · Advanced Excel  

---

## 📌 Featured Projects

### 🛡 Shield Insurance Analytics
- 27K+ customers, ₹989M revenue  
- 18.4% MoM growth insights  
- Tech: Power BI, SQL, Excel  

### 📡 Telecom Post-5G Analysis
- ₹31.9B revenue, 161M users  
- 12.6M churn identified  
- Tech: SQL, Power BI  

### 📊 Business Insights Dashboard
- 10K+ rows processed  
- KPI-driven dashboards  

*(ML + FastAPI projects coming soon 🚀)*

---

## 🎯 Career Goal

To become a **Data Scientist / ML Engineer** building intelligent, scalable systems that solve real-world problems.

---

## 📫 Contact

📧 rktiwary1208@gmail.com  
💼 https://www.linkedin.com/in/YOUR_LINKEDIN/

---

⭐ Thanks for visiting my GitHub profile!
```

### ✅ Key Features Added:

1. **Word-by-word popping animation** for your intro sentence.
2. Easy to **adjust speed** via the `delay += 250` line.
3. Stays fully **Markdown-compatible** for GitHub README.
4. Maintains badges, projects, and layout.

---

If you want, I can make it **even fancier**:

* Add **bounce + scale effect** per word (really "pop" effect)
* Include **color gradient per word**
* Make it fully **mobile responsive** in GitHub README

Do you want me to do that next?
