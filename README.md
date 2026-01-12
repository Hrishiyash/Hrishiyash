
<h1 align="center">Hi 👋, I'm Rishikant Tiwary</h1>

<!-- ===================== TYPING + POPPING ANIMATION ===================== -->
<p align="center">
  <span id="animatedIntro"></span>
</p>

<style>
  /* Container & word style */
  #animatedIntro {
    display: inline-block;
    font-size: 1.3rem;
    font-weight: 600;
    color: #4AA3FF;
    line-height: 2;
    max-width: 800px;
    word-wrap: break-word;
    text-align: center;
  }

  /* Each word */
  #animatedIntro span {
    opacity: 0;
    display: inline-block;
    transform: translateY(20px) scale(0.8);
    transition: all 0.4s cubic-bezier(0.68, -0.55, 0.27, 1.55);
    margin-right: 5px;
  }

  /* Word visible */
  #animatedIntro span.show {
    opacity: 1;
    transform: translateY(0) scale(1);
  }

  /* Responsive */
  @media (max-width: 768px) {
    #animatedIntro {
      font-size: 1.1rem;
    }
  }
</style>

<script>
  // Words for typing + popping
  const introWords = [
    "Aspiring Data Scientist",
    "Machine Learning & AI Enthusiast",
    "FastAPI | Docker | Python Developer",
    "Turning Data into Intelligent Systems"
  ];

  const introEl = document.getElementById('animatedIntro');

  let wordIndex = 0;
  let charIndex = 0;

  function typeWord() {
    if (wordIndex >= introWords.length) return; // Stop after last word

    const currentWord = introWords[wordIndex];
    if (charIndex < currentWord.length) {
      // Create span if first char
      if (charIndex === 0) {
        const span = document.createElement('span');
        introEl.appendChild(span);
      }
      const span = introEl.querySelectorAll('span')[wordIndex];
      span.textContent += currentWord[charIndex];
      charIndex++;
      setTimeout(typeWord, 100); // typing speed per character
    } else {
      // Word completed: show and move to next word
      introEl.querySelectorAll('span')[wordIndex].classList.add('show');
      wordIndex++;
      charIndex = 0;
      setTimeout(typeWord, 300); // delay before next word
    }
  }

  typeWord();
</script>

<!-- ===================== BADGES ===================== -->
<p align="center">
  <a href="https://www.linkedin.com/in/YOUR_LINKEDIN/">
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

I am an **aspiring Data Scientist** with a strong foundation in analytics and business intelligence, currently transitioning toward **Machine Learning, Artificial Intelligence, and backend deployment**.

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
💼 [LinkedIn](https://www.linkedin.com/in/YOUR_LINKEDIN/)

---

⭐ Thanks for visiting my GitHub profile!
```

---

### ✨ Features:

1. **Typing + popping combo** — each word types out character by character, then pops with a bounce.
2. Fully **responsive** — works on mobile.
3. **Clean, professional layout** — badges, projects, career goals, contact info.
4. **Directly paste into README.md** — works on GitHub with no errors.

---

If you want, I can **also make this gradient + neon color version** for your intro that will **really pop visually** on GitHub — it will make your profile stand out.

Do you want me to do that next?
