# Predictive Modeling for Breast Cancer Outcomes

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📋 Project Overview

This repository documents a comprehensive research project on **developing interpretable machine learning models for predicting breast cancer recurrence and survival outcomes**. The project integrates clinical and hematological data to create clinically applicable prognostic tools, following TRIPOD reporting standards.

**Key Achievements:**
- ✅ **Publication**: Article submitted to *npj Breast Cancer (Nature)*
- ✅ **TCC Defense**: Successfully completed undergraduate thesis
- ✅ **International Career**: TOEFL preparation and postgraduate applications underway
- ✅ **Advanced Modeling**: Multi-horizon (2 & 10-year) and subtype-specific models (HR+, HER2+, TNBC)

## 👥 Authors & Supervision

- **Patricia Honorato Moreira** – Student (Inteli)
- **Flavia Santoro** – Co-advisor (Inteli)
- **Luciana Rodrigues Carvalho Barros** – Supervisor (Fundação Faculdade de Medicina)
- **Roger Chammas** – Co-supervisor (Hospital das Clínicas da Faculdade de Medicina da Universidade de São Paulo – HCFMUSP)

## 🏗️ Project Structure

This project evolved through **4 modules** (25 sprints total) from data integration to publication submission:

### Module 1: Foundation & Initial Modeling
- **Focus**: Data integration, preprocessing, and baseline ML models
- **Key Deliverables**: Unified dataset, initial Random Forest/XGBoost/SVM models
- **Timeline**: Basic ML pipeline establishment

### Module 2: Model Refinement & Manuscript Development
- **Focus**: General predictive models and scientific communication
- **Key Deliverables**: SHAP interpretability, Kaplan-Meier analysis, manuscript draft
- **Timeline**: Manuscript structure and general model optimization

### Module 3: Multi-Horizon Expansion
- **Focus**: Transition to multi-horizon recurrence prediction (2 & 10-year)
- **Key Deliverables**: Subtype-specific models (HR+, HER2+, TNBC), expanded dataset
- **Timeline**: Manuscript restructuring and publication preparation

### Module 4: Finalization & Publication
- **Focus**: Complete analysis, publication submission, and career advancement
- **Key Deliverables**: Final manuscript, TCC defense, international application preparation
- **Timeline**: Publication submission and career planning

## 🛠️ Technical Implementation

### Machine Learning Models
- **Traditional ML**: Random Forest, XGBoost, SVM
- **Ensemble Methods**: Stacking Classifier with Logistic Regression
- **Deep Learning**: Keras Neural Networks (MLP)
- **Oversampling**: SMOTE for class imbalance correction

### Data & Features
- **Clinical Data**: Tumor staging, patient demographics, treatment history
- **Laboratory Data**: Hematological markers, inflammatory ratios (NLR, PLR, MLR)
- **Advanced Features**: PCA/UMAP latent features, GMM clustering
- **Time Horizons**: 2-year and 10-year recurrence prediction

### Evaluation & Interpretability
- **Performance Metrics**: AUC-ROC, Precision, Recall, F1-Score, Accuracy
- **Interpretability**: SHAP analysis, feature importance rankings
- **Clinical Validation**: Kaplan-Meier survival curves, calibration plots
- **Cross-Validation**: Stratified k-fold validation across subtypes

### Data Pipeline
```
Raw Data → Cleaning → Feature Engineering → Model Training → Evaluation → Interpretability → Clinical Validation
```

## 📊 Key Results

### Model Performance (AUC Scores)
- **General Model**: ~0.82–0.83
- **Subtype-Specific Models**: ~0.75–0.85 (HR+, HER2+, TNBC)
- **Multi-Horizon Framework**: Consistent performance across 2 & 10-year predictions

### Clinical Impact
- **Interpretability**: SHAP analysis reveals clinically meaningful feature contributions
- **Survival Stratification**: Kaplan-Meier curves demonstrate risk group separation
- **Resource-Limited Settings**: Models designed for global clinical applicability

## 📁 Repository Contents

```
├── Module 1/
│   ├── Public Report (PDF)/
│   └── README.md                 # Data integration & initial modeling
├── Module 2/
│   ├── [PDF Report]
│   └── readme.md                 # Model refinement & manuscript development
├── Module 3/
│   ├── [PDF Report]
│   └── readme.md                 # Multi-horizon expansion
├── Module 4/
│   ├── [TCC Final Version PDF]
│   └── README.md                 # Finalization & publication
└── README.md                     # This file - repository overview
```

## 🔬 Research Methodology

### TRIPOD Compliance
- **Transparent Reporting**: Complete methodology documentation
- **Reproducibility**: Version-controlled Jupyter notebooks
- **Ethical Standards**: Patient data anonymization and privacy protection

### Statistical Rigor
- **Stratified Splitting**: 60% training, 20% validation, 20% testing
- **Cross-Validation**: Robust performance estimation
- **Multiple Metrics**: Balanced evaluation beyond single accuracy measures

## 🎯 Clinical Applications

### Target Use Cases
- **Prognostic Assessment**: Early identification of high-risk patients
- **Treatment Planning**: Personalized therapeutic decision support
- **Resource Allocation**: Optimized follow-up strategies in constrained settings

### Geographic Scope
- **Primary Data**: Single-center Brazilian cohort (HCFMUSP)
- **Global Applicability**: Models designed for international validation
- **Resource Considerations**: Emphasis on cost-effective, accessible biomarkers

## 🚀 Impact & Future Directions

### Academic & Career Impact
- **Research Dissemination**: Publication in *npj Breast Cancer (Nature)*
- **Academic Completion**: TCC defense and knowledge transfer
- **International Advancement**: TOEFL preparation and postgraduate applications
- **Research Foundation**: Established methodology for advanced oncology ML

### Future Research
- **External Validation**: Multi-center studies for generalizability
- **Expanded Cohorts**: Larger datasets for improved model robustness
- **Advanced Techniques**: Integration of genomic and imaging data
- **Clinical Trials**: Prospective validation in treatment decision-making

## 📜 License & Usage

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**Important Notes:**
- All patient data remains confidential and anonymized
- Models are for research purposes; clinical implementation requires validation
- Citation: Please reference the published article when using this work

## 🙏 Acknowledgments

Collaborators: **Inteli**, **Fundação Faculdade de Medicina**, **HCFMUSP**. Special thanks to clinical teams, data managers, and research mentors for advancing oncology predictive modeling.

---

**Status**: Complete research cycle (2024-2025) • Publication submitted • TCC defended • International applications in progress
