# Exploratory Data Analysis of Amino Acid Physicochemical Properties

## Purpose

The purpose of this project is to explore and analyse the key physicochemical properties of amino acids using Python tools such as `pandas`, `matplotlib`, and `seaborn`. The project combines biochemical knowledge with data analysis to identify patterns, trends, and insights in amino acid data.

This project demonstrates:
- Biochemistry domain knowledge
- Data analysis and visualisation skills
- The ability to clean, explore, and communicate data-driven insights

---

## Goals

### 1. Understand the Data
Analyse and summarise amino acid properties, including:
- Molecular weight
- pKa values (COOH, NH₂, and R-group)
- Hydrophobicity index
- Charge at physiological pH
- Polarity and side chain classification

### 2. Generate Visual Insights
Perform exploratory data analysis (EDA) to:
- Explore data distributions
- Compare properties across amino acid groups
- Identify patterns and relationships
- Highlight biochemical groupings (e.g. acidic vs basic)

### 3. Tell a Data-Driven Story
The notebook will guide the reader through:
- Descriptions and biochemical relevance of each variable
- Observations and findings (e.g. most hydrophobic amino acids)
- Clear and informative visualisations
- Well-documented and readable code

### 4. Build a Shareable Portfolio Project
The final output will include:
- A Jupyter Notebook or Python script
- Data visualisations (histograms, scatter plots, heatmaps)
- A well-organised GitHub repository
- A README with a clear explanation of the project and its findings

---

## Key Questions Explored

- What is the distribution of amino acid molecular weights?
- Which amino acids are acidic or basic?
- How does hydrophobicity relate to polarity?
- Which amino acids have extreme pKa values, and why?
- Are there patterns or clusters among physicochemical properties?

---

## Learning Outcomes

| Skill              | Demonstrated by                                      |
|-------------------|-------------------------------------------------------|
| Data cleaning      | Reading and preparing CSV data                        |
| Exploratory analysis | Summary statistics, filtering, grouping            |
| Visualisation      | Charts and plots using Matplotlib and Seaborn        |
| Domain knowledge   | Interpreting data from a biochemical perspective      |
| Communication      | Explaining findings in clear language and structure   |

---


## Set up

1. Install requirements.txt:
    - matplotlib
    - seaborn
    - pandas
    - jupyterlab 
2. Activate jupyterlab and copy token to login on jupyter
`jupyter lab --ip=0.0.0.0 --port=8888 --allow-root --no-browser`
`http://0.0.0.0:8888/lab?token=copythis<token>`
3. Set up Kaggle for downloading data

    ``` bash
        mkdir -p ~/.kaggle
        mv kaggle.json ~/.kaggle/
        chmod 600 ~/.kaggle/kaggle.json
        pip install kaggle
        kaggle datasets download -d alejopaullier/aminoacids-physical-and-chemical-properties
        unzip aminoacids-physical-and-chemical-properties.zip -d data/
        rm aminoacids-physical-and-chemical-properties.zip

    ```
    Zip folder will be downloaded