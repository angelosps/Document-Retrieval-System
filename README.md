# Document Retrieval System 🗂️

A DRS that returns titles and the related passages of scientific articles that contain the answer to a given user question about coronaviruses and in particular COVID-19. I use the [COVID-19 Open Research Dataset (CORD-19)](https://www.semanticscholar.org/cord19).

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Qi_dK-S6spqYDsa18-pgAK_klPBuWjBp?usp=sharing) 


Example outputs from running the models:

> **Question:** What are the coronaviruses?  
  **From paper with title:** Natural Bis-Benzylisoquinoline Alkaloids-Tetrandrine, Fangchinoline, and Cepharanthine, Inhibit Human Coronavirus OC43 Infection of MRC-5 Human Lung Cells  
  **Passage answer:** Coronaviruses (CoVs) are enveloped, positive-sense, single-stranded RNA viruses that infect a broad range of animal species and cause multiple respiratory outcomes of varying severity, including the common cold, bronchiolitis, and pneumonia.
  
> **Question:** Where was COVID-19 discovered?  
  **From paper with title:** Clinical Medicine Optimization Method for Forecasting Confirmed Cases of COVID-19 in China  
  **Passage answer:** In December 2019, a novel coronavirus, called COVID-19, was discovered in Wuhan, China, and has spread to different cities in China as well as to 24 other countries.  
  
> **Question:** Does wearing a mask prevent the spread of COVID-19?  
  **From paper with title:** Transmission of Influenza A in a Student Office Based on Realistic Person-to-Person Contact and Surface Touch Behaviour  
  **Passage answer:** Wearing a mask can control the spread of disease via the long- range airborne, fomite and close contact routes.
  
> **Question:** What are the symptoms of COVID-19?  
  **From paper with title:** The history and epidemiology of Middle East respiratory syndrome corona virus
  **Passage answer:** The clinical presentation of MERS-CoV ranges from flu-like symptoms, i.e., fever and cough in 87% of patients, chills, rigor, rhinorrhea, myalgia, and fatigue, to more severe symptoms, including shortness of breath in 48% of patients and respiratory failure, resulting in the requirement for intubation and ventilation.

You can see all the questions asked in each of the five models in the `Report.pdf` I have provided in this repository as well as some comments and comparisons of the models.
