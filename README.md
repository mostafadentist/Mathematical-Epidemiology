# Mathematical Epidemiology with R 

This repository contains a **teaching portfolio notebook** for Mathematical Epidemiology implemented in **R**.  
It provides a structured walkthrough of classical compartmental models used to understand and forecast epidemics.

<p align="center">
  <a href="https://commons.wikimedia.org/wiki/File:SIR_model_anim.gif#/media/File:SIR_model_anim.gif">
    <img src="https://upload.wikimedia.org/wikipedia/commons/2/20/SIR_model_anim.gif" 
         alt="SIR model animation" width="500">
  </a>
</p>

*Image credit: [Phrontis](https://commons.wikimedia.org/wiki/User:Phrontis),  
licensed under [CC BY‑SA 3.0](https://creativecommons.org/licenses/by-sa/3.0),  
via [Wikimedia Commons](https://commons.wikimedia.org/w/index.php?curid=88245320).*
My previous research in covid spread [https://www.researchgate.net/publication/392512239_Graph-Based_Optimization_for_COVID-19_Testing_Prioritization_A_Network_Science_Approach?_sg%5B0%5D=J-6l8xKRq55xOLC3MZmiLarrIOGVUkwZP3ELj2r0ieQ241OCp2TrqzlybS9RnaVdOQpbV7X1bXQpU1CJC9UyqgzXrCyuU9yjenGEjFAE.InDa-XA2ZsMMprfCAD7jBBrYdGSVvK1mJG2w9aXw1Us2GoobEkrMF8i5cFoHCFQ1ZqaPD8FX41SGWJg7xnP55Q&_tp=eyJjb250ZXh0Ijp7ImZpcnN0UGFnZSI6ImxvZ2luIiwicGFnZSI6InByb2ZpbGUiLCJwcmV2aW91c1BhZ2UiOiJwcm9maWxlIiwicG9zaXRpb24iOiJwYWdlQ29udGVudCJ9fQ]
---

## 📑 Contents

This notebook covers:

1. **Introduction & Setup**  
   - What epidemiological models are, why they matter.  

2. **Basic SIR Model**  
   - Susceptible–Infected–Recovered equations.  
   - Epidemic curves and \(R_0\).  

3. **SEIR Model**  
   - Adds an Exposed compartment for incubation period.  

4. **Extensions**  
   - Births, deaths, vaccination.  

5. **Stochastic Epidemiology**  
   - Gillespie algorithm for random epidemic trajectories.  

6. **Parameter Estimation**  
   - Fit SIR to noisy outbreak data using least squares.  

7. **Control Scenarios**  
   - Simulating interventions: distancing, treatment, vaccination.  

8. **Discussion & Policy Links**  
   - How model results inform public health policy.  

9. **Bayesian Inference (Bonus Section)**  
   - Use MCMC (Stan) to estimate β, γ, and credible intervals for \(R_0\).  

---

## 🎯 Purpose

- To demonstrate **core epidemiological models** in R.  
- To build a **portfolio-quality tutorial** useful for learning and teaching.  
- To bridge **theory → data → policy** with both deterministic and stochastic approaches.  

---

## ⚖️ License Notice

- Code and notebook material licensed under an open-source license (e.g., MIT).  
- Included image is **not** under this repo’s code license:  
  - “SIR model anim.gif” by [Phrontis](https://commons.wikimedia.org/wiki/User:Phrontis),  
    licensed under [CC BY‑SA 3.0](https://creativecommons.org/licenses/by-sa/3.0).  

---
