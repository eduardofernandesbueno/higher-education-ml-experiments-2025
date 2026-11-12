# Higher Education Machine Learning Experiments — 2025

**Exploratory Data Science · Python · Jupyter Notebooks · Data Engineering · Educational Analytics**

**Project Type:** Experimental extension of an undergraduate Data Science capstone  
**Original Academic Institution:** Virtual University of the State of São Paulo (UNIVESP), Brazil  
**Year:** 2025  
**Research Domain:** Higher Education Analytics and Educational Data Mining  
**Repository Maintainer:** Eduardo Fernandes Bueno  
**Current Professional Affiliation:** Research & Development — Information Technology Office (ATI), State University of Londrina (UEL), Brazil

[Original UNIVESP Capstone](https://github.com/eduardofernandesbueno/univesp-higher-education-dropout-2025) · [Professional Portfolio](https://eduardofernandesbueno.github.io/) · [GitHub Profile](https://github.com/eduardofernandesbueno)

---

## 1. Overview

This repository preserves exploratory software development and machine learning experimentation associated with the extension of a collaborative 2025 Data Science capstone project at UNIVESP.

The original capstone investigated Brazilian higher education indicators using public data from the National Institute for Educational Studies and Research Anísio Teixeira (INEP/MEC).

Its principal objective was to investigate computational approaches to collecting, processing, analyzing, and visualizing information about student admissions, course completion, and dropout-related indicators.

Following that academic work, additional experiments and development activities were undertaken to explore the organization of analytical code, Python-based data processing, Jupyter notebooks, and machine learning workflows.

This repository represents part of that exploratory process.

**Important distinction:** It is not the canonical repository of the original UNIVESP capstone, nor does it claim to contain a separately validated or production-ready machine learning system.

---

## 2. Project Motivation

The original capstone highlighted several practical challenges in educational data science:

- Heterogeneous historical datasets.
- Inconsistent data schemas and variable names.
- Missing and anomalous values.
- Difficulties integrating educational indicators.
- Challenges in preparing data for predictive modeling.
- Limited explanatory power of some machine learning features.
- Reproducibility and environment management.
- Large dataset storage and version control.

These challenges motivated additional experimentation with analytical workflows and software organization.

This repository documents an exploratory stage in the evolution from academic data analysis toward more systematic data engineering and machine learning practices.

---

## 3. Objectives

The experimental extension sought to investigate opportunities for improving and organizing computational work related to higher education analytics.

The areas explored or considered included:

1. Organizing Python-based analytical code and development materials.
2. Supporting notebook-based experimentation.
3. Investigating data preprocessing and preparation workflows.
4. Exploring machine learning development practices.
5. Working with data derived from public educational sources.
6. Managing project configuration and development files.
7. Investigating version control challenges involving larger research artifacts.
8. Preserving intermediate development evidence and technical limitations.

These objectives describe the exploratory scope. They do not establish that each proposed feature was completed or successfully validated.

---

## 4. Relationship to the Original UNIVESP Capstone

### Original Academic Project — 2025

**Portuguese title:**

*Análise de Dados Educacionais em Instituições de Ensino Superior: Um Sistema para Monitoramento de Ingresso, Permanência e Evasão*

**English translation:**

*Educational Data Analysis in Higher Education Institutions: A System for Monitoring Admission, Persistence, and Dropout*

**Institution:** Virtual University of the State of São Paulo (UNIVESP)  
**Degree:** Bachelor of Science in Data Science  
**Year:** 2025  
**Academic Format:** Collaborative undergraduate capstone

The original project examined educational data engineering and analytical modeling using public INEP/MEC microdata.

Its documented technological scope included:

- Python-based automated data collection.
- Data processing and transformation.
- Exploratory data analysis.
- Statistical visualization.
- Supervised machine learning.
- Linear Regression and Random Forest experiments.
- Neural network and transfer learning experiments.
- Temporal model validation.
- Interactive educational dashboards.

The original capstone remains the authoritative source for those implementation and research claims.

**Canonical repository:**

https://github.com/eduardofernandesbueno/univesp-higher-education-dropout-2025

### Purpose of This Extension

Unlike the original academic deliverable, this repository focuses on exploratory development, additional organization, and investigation of machine learning workflows.

It should not be cited as an independent capstone or a second scientific publication.

---

## 5. Technology Stack

### 5.1 Technologies Identified in This Repository

| Technology | Role |
|---|---|
| Python | Programming language for experimental analytical work |
| Jupyter Notebook | Notebook-based development materials |
| Visual Studio Code | Development configuration associated with `.vscode/` |
| Git | Source version control |
| GitHub | Repository hosting and change history |
| Git LFS | Large-file tracking configuration |

The GitHub language classification identifies both Python and Jupyter Notebook content.

The repository also contains Git configuration files and local development configuration materials.

### 5.2 Related Technologies from the Original Capstone

The original UNIVESP capstone documented the use of additional technologies, including:

| Area | Technologies |
|---|---|
| Data Processing | Pandas, NumPy |
| Data Acquisition | Requests, CSV, Zipfile |
| Machine Learning | scikit-learn |
| Predictive Algorithms | Linear Regression, Random Forest |
| Neural Networks | TensorFlow, Keras |
| Data Visualization | Matplotlib, Seaborn |
| Interactive Dashboards | Streamlit |
| Evaluation | Holdout Validation, Temporal Validation, MSE, R² |

These tools provide context for the originating academic research.

**They are not asserted as verified dependencies of this repository unless confirmed by its actual source files, notebooks, or environment specifications.**

---

## 6. Repository Structure

The main branch currently exposes the following top-level structure:

```text
higher-education-ml-experiments-2025/
├── .vscode/
├── informacao/
├── .gitattributes
├── .gitignore
├── README.md
└── log_erros.txt
```

### Directory and File Roles

| Path | Purpose |
|---|---|
| `.vscode/` | Development environment configuration |
| `informacao/` | Project materials and experimental files |
| `.gitattributes` | Git attributes, including large-file tracking rules |
| `.gitignore` | Exclusion rules for generated or local files |
| `README.md` | Project documentation |
| `log_erros.txt` | Historical development and error information |

The precise contents of the `informacao/` directory should be examined individually when assessing reproducibility and implementation maturity.

The presence of notebook-related language statistics does not, by itself, establish a complete executable notebook pipeline.

---

## 7. Data Engineering Context

The originating research investigated the acquisition and preparation of public higher education data.

The conceptual data processing workflow included:

**Official Data Sources → Data Acquisition → Raw Data → Cleaning and Standardization → Analytical Datasets → Exploratory Analysis → Modeling Experiments → Visualization**

This workflow describes the broader research architecture.

It should not be interpreted as evidence that a complete implementation of every stage exists in this experimental repository.

### Data Engineering Challenges

The original research identified several relevant technical problems:

- Handling heterogeneous CSV datasets.
- Standardizing variable names.
- Processing missing observations.
- Managing different file encodings.
- Organizing raw and processed datasets.
- Ensuring analytical consistency.
- Maintaining reproducible development environments.

These challenges remain useful areas for further experimentation.

---

## 8. Machine Learning Research Context

The original capstone investigated supervised prediction of educational indicators and identified important limitations.

Models explored in the originating study included:

- Linear Regression.
- Random Forest.
- Artificial Neural Networks.
- Transfer Learning and Fine-Tuning experiments.

Evaluation methods included historical train/test separation and regression metrics.

### Scientific Considerations

An important finding of the original work was the risk of target leakage when predictors were mathematically related to the outcome.

The broader research also identified low predictive explanatory power when models relied on restricted sets of educational variables.

These findings informed subsequent interests in:

- Feature selection and engineering.
- Data validation.
- Temporal evaluation.
- Model generalization.
- Experimental traceability.
- More reliable analytical workflows.

**This repository does not claim independently reproduced performance improvements over the original capstone.**

No additional accuracy, MSE, R², or other model-performance claims are made without a corresponding verified experiment.

---

## 9. Development and Experimentation

This repository preserves an exploratory development stage rather than a fully packaged software product.

Activities represented by the repository include Python-related experimentation, notebook materials, project configuration, and development records.

### Development Practices

The broader engineering approach emphasizes:

- Incremental development.
- Version control.
- Separation of experimental concerns.
- Inspection of intermediate results.
- Documentation of errors.
- Iterative improvement.

### Error and Development Records

The presence of `log_erros.txt` is evidence that development difficulties were recorded.

Such logs may be useful for understanding previous execution problems, including data ingestion and environment-related issues.

However, raw logs should be reviewed before public reuse to ensure they do not expose confidential information, personal identifiers, local credentials, or internal paths.

---

## 10. Reproducibility and Current Maturity

### What Is Publicly Documented

The repository provides:

- Historical version-control information.
- Python and Jupyter-related files.
- Development configuration.
- Experimental materials.
- Git LFS configuration.
- A record of development errors.

### What Has Not Been Independently Verified

At the current documentation stage, the following have not been established:

- A complete, executable end-to-end pipeline.
- A validated dependency installation procedure.
- Reproducible training and evaluation scripts.
- Complete availability of historical datasets.
- Independent reproduction of model metrics.
- Successful deployment of a predictive application.
- Production-grade data quality controls.
- Automated integration or continuous delivery pipelines.

The repository should therefore be treated as an exploratory research and development archive.

---

## 11. Limitations

This project has several important limitations.

### Experimental Scope

The repository represents an extension of an earlier academic project rather than an independently completed research system.

### Documentation

The current repository does not demonstrate all the directories and components described in earlier planning documents.

### Execution

A validated, one-command reproduction procedure has not been established.

### Machine Learning

No new independently validated predictive performance is claimed.

### Data and Artifacts

Large files, experimental datasets, and historical dependencies may require separate verification.

### Software Maturity

The repository is not presented as a production-ready application, public API, or institutionally deployed analytical service.

---

## 12. Future Engineering Improvements

The following improvements are proposed rather than completed.

### Repository Organization

- Document the contents of experimental directories.
- Distinguish active source files from historical artifacts.
- Remove unnecessary generated files after appropriate review.
- Preserve historical source-control evidence.
- Improve `.gitignore` and Git LFS policies where necessary.

### Reproducibility

- Verify a supported Python environment.
- Document dependencies and versions.
- Identify notebook execution order.
- Define representative test datasets.
- Create repeatable execution instructions.

### Data Engineering

- Establish data schemas and validation rules.
- Improve preprocessing organization.
- Separate input data from generated outputs.
- Document data lineage and provenance.

### Machine Learning

- Formalize experimental questions.
- Define explicit target variables.
- Improve feature validation.
- Implement leakage checks.
- Apply temporal validation where appropriate.
- Record experimental metrics and configurations.

### Software Quality

- Introduce automated tests.
- Improve logging and error handling.
- Document expected inputs and outputs.
- Review public repository security.
- Improve portability across development environments.

---

## 13. Academic Attribution

This repository originates from experimental extensions associated with the 2025 UNIVESP Data Science capstone.

The original academic project was developed collaboratively by:

- Ariel Abrahão Gadia
- Bruna Camila Soares Cabral
- Edgar Clemente Bispo
- Eduardo Alonso Duarte
- Eduardo Fernandes Bueno
- Juergen Johann Moura Martins
- Roberto Akiba de Oliveira
- Samuel da Cruz Souza

**Academic Advisor:** Maria Eduarda Guillen Diomásio

The original team retains appropriate attribution for the collaborative academic work.

This experimental repository is maintained by Eduardo Fernandes Bueno.

Its ownership should not be interpreted as sole authorship of the original capstone, its research conclusions, or the work of other contributors.

---

## 14. Professional Context — ATI/UEL

Eduardo Fernandes Bueno is a Data Engineer, Data Scientist, and M.Sc. candidate in Computer Science at the State University of Londrina (UEL), Brazil.

He contributes to Research & Development activities at UEL's Information Technology Office (**ATI/UEL**), with interests and experience in:

- Data Engineering.
- Data Architecture.
- Data Integration.
- Data Governance.
- Machine Learning.
- Applied Research.
- Software Engineering.
- Scientific Reproducibility.
- Privacy and Responsible AI.

His academic background includes degrees in Data Science, Information Technology, and Law.

The interdisciplinary combination of computing and legal training informs his professional interests in reliable data systems, institutional governance, privacy, and accountable analytical decision-making.

### Institutional Clarification

This repository documents independent exploratory work related to a UNIVESP academic project.

It is **not an official ATI/UEL or UNIDATA deliverable**.

The reference to ATI/UEL identifies Eduardo's subsequent professional affiliation and does not imply institutional funding, authorship, supervision, or endorsement of these experiments.

---

## 15. Responsible Research and Data Governance

Educational data analysis requires attention to:

- Data provenance.
- Privacy and confidentiality.
- Appropriate use of publicly available datasets.
- Analytical validity.
- Bias and representativeness.
- Reproducibility.
- Institutional accountability.

Predictive results should not be treated as sufficient evidence for decisions affecting individual students.

This repository is intended to preserve experimental learning and development materials.

---

## 16. Reuse and Intellectual Property

The repository is publicly accessible, but public accessibility does not automatically grant unrestricted reuse rights.

The original README states that prior authorization is required for reuse of its contents.

Any future licensing changes should account for:

- Ownership of the experimental code.
- Rights of the original UNIVESP capstone contributors.
- Third-party software licenses.
- Data source terms.
- Rights associated with any reused academic materials.

Until a suitable license and authorship review is completed, users should not assume that the absence of a standard license grants permission for unrestricted redistribution or modification.

---

## 17. Related Work

### Original UNIVESP Data Science Capstone — 2025

**Higher Education Dropout Analytics**

https://github.com/eduardofernandesbueno/univesp-higher-education-dropout-2025

The original collaborative academic project documents data acquisition, preprocessing, machine learning experiments, evaluation, and educational analytics visualization.

### UEL Human–Computer Interaction Coursework — 2025

**Human–Computer Interaction for Educational Analytics**

https://github.com/eduardofernandesbueno/uel-hci-educational-dashboard-2025

A separate academic activity investigated usability, accessibility, and interaction design using an educational analytics system as its case study.

These are distinct projects with different research and engineering objectives.

---

## 18. Professional and Academic Links

**Eduardo Fernandes Bueno**

- **GitHub:** https://github.com/eduardofernandesbueno
- **Professional Portfolio:** https://eduardofernandesbueno.github.io/
- **LinkedIn:** https://www.linkedin.com/in/eduardofernandesbueno/
- **ORCID:** https://orcid.org/0009-0000-8620-0211
- **Curriculum Lattes:** http://lattes.cnpq.br/8716619580595259

---

## 19. Summary

This repository documents an exploratory stage of Data Science and Machine Learning development following a collaborative 2025 UNIVESP capstone.

Its value lies in preserving:

- Python and Jupyter experimentation.
- Data preparation and workflow exploration.
- Development configuration.
- Historical engineering artifacts.
- Challenges encountered during experimental development.
- Opportunities for improving reproducibility and software quality.

The repository is maintained as a distinct record of experimentation rather than a duplicate of the original capstone or a claim of independently validated Machine Learning results.

---

**Experimental Development — UNIVESP Capstone Extension, 2025**

*Python · Jupyter · Data Science · Machine Learning · Educational Analytics*

**Maintained by Eduardo Fernandes Bueno — R&D at ATI/UEL, Brazil.**
