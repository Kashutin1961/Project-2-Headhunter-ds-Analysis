# 📊 Project 2: Analysis of HeadHunter Job Postings

This project is part of the **SkillFactory Data Science course** and focuses on analyzing job postings for Data Science roles from HeadHunter.  
The repository includes SQL queries, Python-based data processing, and environment setup for reproducibility.

---

## 📁 Project Structure

- **Python_and_SQL.ipynb** — main notebook with SQL queries executed via Python
- **PROJECT_2_Анализ_вакансий_из_HeadHunter.ipynb** — test notebook  
- **Python_and_SQL.ipynb** — SQL queries executed via Python  
- **Python_and_SQL_Commented.ipynb** — draft annotated version of SQL logic  
- **SQL_uppercase_diff.txt** — SQL formatting comparison created by Copilot  
- **environment.yml** — Conda environment file for reproducibility 

---

## 🧪 Environment Setup

This project uses a **Conda environment** named `Conda_SkillsFactory`.  
It includes essential libraries for data analysis, PostgreSQL integration, and visualization.  

To create the environment:

```bash
conda env create -f environment.yml
```

To activate the environment:

```bash
conda activate Conda_SkillsFactory
```

---

## 📦 Key Packages

Below is a selection of important packages defined in `environment.yml`:  

- **Numerical & Scientific Computing**: numpy, scipy, bottleneck, numexpr, mkl  
- **Data Handling**: pandas  
- **Visualization**: matplotlib-base, contourpy, cycler, fonttools  
- **Utilities**: setuptools, wheel, six, typing-extensions, sortedcontainers, xmltodict  
- **System & Compression**: bzip2, brotli-python, zlib  

The full environment is available in the [`environment.yml`](./environment.yml) file.  
It uses both `anaconda` and `defaults` channels.

---

## 🚀 Getting Started

1. Clone the repository or download the project files.  
2. Set up the Conda environment as described above.  
3. Open the main notebook and follow the analysis steps.  

---

## ✨ Key Features

- SQL-based filtering and aggregation of job postings  
- Python logic for salary normalization and skill counting  
- Reproducible environment via Conda (`environment.yml`)  
- Inline comments and uppercase SQL formatting for readability  
- Integration with VS Code Copilot Agent for assisted editing and annotation  

---

## 🛠 Development Notes

- Environment exported using:  

  ```bash
  conda env export > environment.yml
  ```

- Compatible with **Python 3.13**  
- Tested in the `Conda_SkillsFactory` environment  
- Data sources are simulated or extracted from HeadHunter via SQL queries  

---

## 📬 Feedback

For questions, suggestions, or improvements, please open an **Issue** or contact the project author.  
