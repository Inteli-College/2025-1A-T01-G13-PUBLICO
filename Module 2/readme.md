# Public Research Module 2 Report
## Authors:

- Patricia Honorato Moreira – Student (Inteli)
  
- Jefferson Silva – Co-supervisor (Inteli)
  
- Luciana Rodrigues Carvalho Barros – Supervisor (Fundação Faculdade de Medicina)
  
- Roger Chammas – Co-supervisor (Hospital das Clínicas da Faculdade de Medicina da Universidade de São Paulo - HCFMUSP)

## Research Area

This project focuses on developing interpretable and clinically applicable machine learning models to predict 10-year recurrence or death in breast cancer patients. The work follows TRIPOD reporting standards and leverages clinical and laboratory data to enhance prognostic accuracy.

---

## Overview of Sprints

### Sprint 1
**Objective:** Initiate scientific communication materials and establish manuscript structure.  
**Activities:**
- Designed a scientific poster summarizing project objectives, methodology, and preliminary results for conference presentation.
- Drafted the Introduction section of the manuscript, including clinical background, project motivation, and study aims.
- Defined the full manuscript structure to align with academic publication standards.
- Generated initial visualizations for poster and manuscript figures (laboratory marker distributions, prognostic ratios).

---

### Sprint 2
**Objective:** Develop the general predictive model and document technical methodology.  
**Activities:**
- Completed Methods and Results sections describing the full analytical pipeline (cohort selection to model interpretation).
- Developed a general predictive model using Random Forest, XGBoost, SVM, and Stacked Ensemble methods based on pre-treatment lab data.
- Applied SMOTE to correct class imbalance; evaluated performance via AUC, precision, recall, and SHAP interpretability.
- Conducted preliminary Kaplan–Meier survival analysis stratifying patients by predicted risk.
  
**Note:** Subtype-specific models postponed due to pending tumor subtype data access.

---

### Sprint 3
**Objective:** Refine manuscript drafts and enhance modeling reproducibility.  
**Activities:**
- Completed first draft of the Results section, integrating:
  - Performance metrics and confidence intervals.
  - SHAP analysis for model interpretability.
  - Survival analysis by predicted risk groups.
- Organized project notebooks for clarity and reproducibility:
  - **Notebook 1:** Data preparation, exploratory analysis, feature engineering.
  - **Notebook 2:** Model training, feature selection, hyperparameter tuning, evaluation structure.
- Ensured modeling pipeline alignment with TRIPOD guidelines for transparent reporting.

---

### Sprint 4
**Objective:** Contextualize results and draft the Discussion section.  
**Activities:**
- Completed first version of the Discussion section addressing:
  - Performance and stability of the stacked ensemble model (ROC-AUC ~0.82–0.83).
  - Comparisons with existing prognostic tools.
  - Alignment of model interpretability with clinical expertise (tumor staging, inflammatory biomarkers).
  - Clinical applicability in resource-limited settings.
  - Study limitations (single-center data, need for external validation).

---

### Sprint 5
**Objective:** Consolidate evaluation, interpretability, and survival analyses in a unified notebook; draft article abstract.  
**Activities:**
- Combined evaluation components into one comprehensive notebook, including:
  - Performance metrics for all models (Random Forest, XGBoost, SVM, Stacking): AUC, accuracy, precision, recall.
  - ROC curves for individual models and combined performance comparison.
  - Global feature importance (Random Forest, XGBoost).
  - SHAP interpretability analysis.
  - Kaplan–Meier survival analysis by risk groups.
- Drafted scientific abstract summarizing methodology, key results, and clinical relevance.

---

## Project Status

- Major manuscript sections (Introduction, Methods, Results, Discussion, Abstract) prepared but not finalized.
- Completing the manuscript for submission remains a priority for the next module.

---

## Conclusions

- Module 2 delivered substantial progress in:
  - General model development.
  - Interpretability analyses (SHAP, feature importance).
  - Survival stratification (Kaplan–Meier).
  - Manuscript drafting.
- Foundations are in place for:
  - Subtype-specific models.
  - External validation.
  - Scientific dissemination.

---

## Next Steps

- Finalize the complete article manuscript for peer-reviewed journal submission.
- Develop and evaluate prognostic models for specific tumor subtypes (Luminal, HER2+, Triple Negative).
- Perform additional exploratory analyses (PCA, UMAP) to characterize data structure if needed for publication.
- Enhance reproducibility, technical documentation, and figure quality to meet publication standards.

---

## Notes

This public report summarizes activities within the clinical predictive modeling field for oncology, ensuring confidentiality of sensitive data and internal project details.
