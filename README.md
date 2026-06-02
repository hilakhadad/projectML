# 🔬 Feature Selection Benchmark — Machine Learning Project

A comparative study of **7 feature selection algorithms** across multiple datasets, evaluating their impact on classification performance.

Built with Python & Jupyter Notebooks as part of a Machine Learning course at Ben-Gurion University.

---

## 🎯 Goal

Identify which feature selection method best improves classifier accuracy across diverse datasets, using statistical tests to validate results.

---

## 🧪 Methods Compared

| Algorithm | Type |
|-----------|------|
| Algo1 (custom) | Filter |
| Algo2 / New Algo2 | Filter |
| MRMR | Filter (Max Relevance Min Redundancy) |
| RFE | Wrapper (Recursive Feature Elimination) |
| ReliefF | Filter |
| SelectFdr | Filter (False Discovery Rate) |

---

## 📊 Datasets

- Multiple real-world datasets (medical, benchmark)
- - Includes **SPECTF Heart** dataset as toy problem baseline
  - - All datasets cleaned and preprocessed before feature selection
   
    - ---

    ## 🧮 Statistical Evaluation

    - **Friedman test** — non-parametric comparison across all algorithms
    - - **Post-hoc tests** — pairwise significance analysis
      - - Results summarized in comparison tables
       
        - ---

        ## 🛠️ Tech Stack

        | Tool | Purpose |
        |------|---------|
        | Python | Core language |
        | scikit-learn | ML models & feature selection |
        | pandas / numpy | Data processing |
        | scipy | Statistical tests |
        | Jupyter Notebook | Analysis & visualization |

        ---

        ## 📁 Files

        | File | Description |
        |------|-------------|
        | `toy_problem.ipynb` | Baseline experiment on SPECTF dataset |
        | `cleaningProcess.ipynb` | Data loading, cleaning & preprocessing |
        | `run files/runAlgo*.ipynb` | Run each of the 7 feature selection algorithms |
        | `part_4_code.ipynb` | Performance comparison across algorithms |
        | `Friedman_and_posthoc.ipynb` | Statistical significance testing |

        ---

        ## 🚀 Getting Started

        1. Download the datasets mentioned in the report
        2. 2. Run `cleaningProcess.ipynb` first to prepare clean datasets
           3. 3. Run each algorithm notebook in `run files/`
              4. 4. Run `part_4_code.ipynb` to compare results
                 5. 5. Run `Friedman_and_posthoc.ipynb` for statistical validation
                   
                    6. ```bash
                       pip install scikit-learn pandas numpy scipy jupyter
                       ```

                       ---

                       ## 📌 Key Findings

                       - Feature selection significantly reduces dimensionality without sacrificing accuracy
                       - - No single algorithm dominates across all datasets — results are dataset-dependent
                         - - Statistical tests confirm meaningful performance differences between methods
