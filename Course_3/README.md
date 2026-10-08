# From Data to Decisions
### Explore, Sample, and Test Hypotheses

<p align="center">
  <img src="https://img.shields.io/badge/Google-Advanced%20Data%20Analytics-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Google Advanced Data Analytics">
  <img src="https://img.shields.io/badge/Course-03-7C3AED?style=for-the-badge" alt="Course 3">
  <img src="https://img.shields.io/badge/Focus-Statistics-14B8A6?style=for-the-badge" alt="Statistics">
  <img src="https://img.shields.io/badge/Workflow-PACE-F97316?style=for-the-badge" alt="PACE workflow">
</p>

> Coursework for **Course 3** of the **Google Advanced Data Analytics** certificate program. These labs build statistical thinking skills, from describing data and exploring distributions to sampling, confidence intervals, and hypothesis testing.

## Contents

- [About the coursework](#-about-the-coursework)
- [Repository structure](#-repository-structure)
- [Tools](#-tools)
- [Topics and workflow](#-topics-and-workflow)
- [Running the notebooks](#-running-the-notebooks)

## About the coursework

This repository contains five course labs and an end-of-course TikTok project. The labs use EPA air quality data to practice descriptive statistics and statistical inference. The final project applies data exploration and hypothesis testing to TikTok video data.

Each lab includes an **Activity** notebook and, where provided, an **Exemplar** notebook with a worked example. CSV files used by the notebooks are kept alongside them.

## Repository structure

```text
.
├── README.md
├── Lab_course_3_module_1/
│   ├── Activity_Explore descriptive statistics.ipynb
│   ├── Exemplar_Explore descriptive statistics.ipynb
│   └── c4_epa_air_quality.csv
├── Lab_course_3_module_2/
│   ├── Activity_Explore probability distributions.ipynb
│   ├── Exemplar_Explore probability distributions.ipynb
│   └── modified_c4_epa_air_quality.csv
├── Lab_course_3_module_3/
│   ├── Activity_Explore sampling.ipynb
│   ├── Exemplar_Explore sampling.ipynb
│   └── c4_epa_air_quality.csv
├── Lab_course_3_module_4/
│   ├── Activity_Explore confidence intervals.ipynb
│   ├── Exemplar_Explore confidence intervals.ipynb
│   └── c4_epa_air_quality.csv
├── Lab_course_3_module_5/
│   ├── Activity_Explore hypothesis testing.ipynb
│   ├── Exemplar_Explore hypothesis testing.ipynb
│   └── c4_epa_air_quality.csv
└── End_of_course_project/
    ├── Activity_Course 4 TikTok project lab.ipynb
    ├── tiktok_dataset.csv
    └── images/
        ├── Analyze.png
        ├── Construct.png
        ├── Execute.png
        ├── Pace.png
        └── Plan.png
```

## Tools

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas">
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white" alt="SciPy">
  <img src="https://img.shields.io/badge/Statsmodels-4051B5?style=flat-square" alt="Statsmodels">
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square" alt="Matplotlib">
  <img src="https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square" alt="Seaborn">
</p>

| Tool | How it is used |
|---|---|
| **Python** | Running analyses in Jupyter notebooks |
| **pandas** | Loading, transforming, and summarizing tabular data |
| **NumPy** | Numerical calculations and simulation |
| **SciPy** | Probability distributions and statistical tests |
| **Statsmodels** | Statistical modeling and inference |
| **Matplotlib** | Plotting and customizing charts |
| **Seaborn** | Statistical data visualization |

## Topics and workflow

### Statistical topics

- Descriptive statistics and data summaries;
- Probability distributions;
- Sampling and sampling distributions;
- Confidence intervals;
- Hypothesis testing and interpreting results.

### PACE — A structured workflow

The end-of-course project uses the **PACE** framework to structure the analysis:

| Stage | Purpose |
|---|---|
| **P — Plan** | Define the business question and analysis goals |
| **A — Analyze** | Explore and prepare the data, then perform statistical analysis |
| **C — Construct** | Communicate the findings with clear visualizations and explanations |
| **E — Execute** | Present conclusions and recommend next steps |

## Running the notebooks

Install Python and the required libraries:

```bash
python -m pip install jupyterlab pandas numpy scipy statsmodels matplotlib seaborn
```

Open a notebook in **JupyterLab**, **Jupyter Notebook**, or **Visual Studio Code**. Run it from its lab or project folder so the notebook can find the CSV file stored alongside it.

---

<p align="center">
  <sub>Coursework repository · Google Advanced Data Analytics · Course 3</sub>
</p>
