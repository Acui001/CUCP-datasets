# CUCP-datasets

**CUCP: A Chinese User Comment Dataset Focused on Urban Parks**

📌 *Status: Under Review*

---

In this paper, we propose a Chinese user comment dataset focused on urban parks, named **CUCP**.

First, the dataset is sourced from popular Chinese review platforms: **Dianping**, **Ctrip**, and **Xiaohongshu**.  
Second, the reviews cover two aspects: **sentiment** and **sensory perception**. The sentiment reviews are classified as *positive* or *negative*, while the sensory reviews are categorized into **vision**, **touch**, **taste**, **smell**, and **hearing**.  
Third, our dataset contains **103,831** entries, which surpasses the dataset sizes of most related studies, reflecting its richness and diversity.  
Lastly, we fine-tuned several widely-used NLP models, including **BERT**, **RoBERTa**, **ELECTRA**, and **XLNet**. The experimental results show that for both sentiment and sensory classification tasks, the models achieve **accuracy, precision, recall, and F1 scores all above 90%**, indicating the high quality and utility of the CUCP dataset.

---

### 🧬 Data Processing Workflow

The following figure illustrates the main steps involved in constructing the CUCP dataset:

![CUCP data processing steps for creating the CUCP dataset](CUCP_prosess.png)

---
#### 🧮 Label Distribution:

| Sensory Category | Total | Positive | Negative |
|------------------|--------|----------|----------|
| Touch            | 23,764 | 18,901   | 4,863    |
| Vision           | 70,321 | 56,331   | 13,990   |
| Taste            | 5,741  | 4,340    | 1,401    |
| Smell            | 1,876  | 1,701    | 175      |
| Sound            | 2,129  | 1,802    | 327      |

This structured labeling makes the CUCP dataset suitable for **multi-class**, **multi-label**, and **binary sentiment** classification tasks.

---

### 📂 Current Availability

> 🔒 **The full dataset will be publicly released after the paper is accepted.**

Currently, we have released a small portion of sample data for demonstration and validation purposes.  
You can find the sample file here: **[demo_CUCP.csv](demo_CUCP.csv)**.

---

### 🔗 Repository Link

The dataset will be fully available at:  
**https://github.com/Acui001/CUCP-datasets**

---

### 📮 Contact

For questions or early collaboration inquiries, please contact:  
📧 acuicuiemail@163.com
