# Scientific Field Growth Analysis (2020–2023) using OpenAlex API

This repository contains a Python-based data analysis pipeline to identify the fastest-growing scientific research fields between 2020 and 2023. The data is sourced from the OpenAlex API, which provides open metadata on scholarly publications worldwide.

## 📈 Key Insight: Oncology & Cancer Research

Among all analyzed fields, **Cancer Research and Oncology** have shown some of the **most significant growth rates** in scientific output between 2020 and 2023.  
This trend reflects the increasing global focus on immuno-oncology, targeted therapies, and advanced biologics.  

With the oncology market expected to surpass **$500 billion by 2030**, this growth in academic output also signals:
- intensified pharmaceutical R&D,
- rising venture capital and biotech funding,
- and strong demand for innovation in cancer diagnostics and treatment.

This analysis may support investors, researchers, and policymakers in identifying emerging high-impact areas in science and medicine.

## 📊 Features

- Uses the [OpenAlex API](https://openalex.org) to extract concept-level metadata
- Calculates % growth in research output for each field (2020 vs 2023)
- Filters and visualizes the **Top 20 fastest growing fields**
- Written in clean, modular Python using `requests`, `pandas`, and `matplotlib`

## 🔍 Example Output

Bar chart showing the top 20 fields with the highest publication growth rates, highlighting cancer-related areas at the top.

## 🧠 How It Works

1. Query the OpenAlex API for top scientific concepts by publication count
2. Extract and compare annual publication counts from 2020 and 2023
3. Calculate relative growth percentage for each field
4. Output a sorted DataFrame and a horizontal bar plot

## 🔗 Data Source

This analysis uses public domain metadata from [OpenAlex.org](https://openalex.org), made available under the [CC0 1.0 Universal (Public Domain Dedication)](https://creativecommons.org/publicdomain/zero/1.0/).

---

## 🧪 Use Cases

- Horizon scanning for emerging scientific domains
- R&D prioritization
- Academic research trend monitoring
- Strategic investment insights for biotech and healthcare sectors

## 📝 License

This project is licensed under the MIT License.  
Feel free to use, modify, and share the code.

