# Bridging Psychological Distance: Understanding Student Perceptions Toward AI and Cloud Computing

This project investigates how university students perceive advanced technologies—specifically Artificial Intelligence (AI) and cloud computing—in educational contexts. By applying **Exploratory Factor Analysis (EFA)** and **Multiple Linear Regression**, this study reveals how psychological distance varies by student demographics, informing inclusive technology design and adoption strategies.

---

## Research Goals

1. **Measure** psychological distance across two dimensions:
   - *Social distance*: “People like me use this.”
   - *Hypothetical distance*: “I’ll use this soon.”

2. **Identify** how student demographic factors (e.g., race, gender, major) influence perceived distance.

3. **Translate** findings into actionable insights for inclusive tech education and engagement.

---

## Methodology

- **Type**: Survey-based, theory-driven quantitative research  
- **Participants**: 232 university students from diverse academic and demographic backgrounds  
- **Instruments**:  
  - 45-item Likert-scale survey  
  - Constructs from **Construal Level Theory** (CLT) and **Technology Acceptance Model** (TAM)  

- **Analysis Tools**:  
  - R (tidyverse, psych, GPArotation)  
  - Exploratory Factor Analysis  
  - Multiple Linear Regression  
  - Data visualization and preprocessing via R and Qualtrics

---

## Code Overview

| File | Purpose |
|------|---------|
| `data_cleaning_and_preprocessing.R` | Recode and preprocess survey responses |
| `efa_analysis.R` | Run factor analysis and extract reliable subscales |
| `linear_modeling.R` | Model how demographics predict perceived tech distance |
| `final_scoring.R` | Compute factor scores using weighted item loadings |

---

## Key Findings

- Students with different majors and racial/ethnic identities perceive AI and cloud tech differently.
- Earlier exposure to tech via coursework or role models reduces psychological distance.
- Factor analysis revealed consistent, interpretable structures across technology types.

---

## Implications

- **Equity-first design**: Consider identity-informed differences in perception and trust when designing tech tools or educational programs.
- **Curriculum planning**: Introduce emerging tech early to normalize use and lower social distance barriers.
- **UX strategy**: Psychological distance can be a valuable metric in assessing product readiness and messaging.

---

## Citation 

Xu, X., Dai, A., Wei, S., & Tan, L. (2024, October). WIP: Examining Psychological Distance Perceptions Towards Advanced Technologies among University Students. In 2024 IEEE Frontiers in Education Conference (FIE) (pp. 1-5). IEEE.

---

## 📂 License

This work is released under the MIT License. See [LICENSE](LICENSE) for details.
