# The-Sugar-Trap-Market-Gap-Analysis
The Sugar Trap Market Gap Analysis
# 🍭 The Sugar Trap: Blue Ocean Market Gap Analysis

## 🧠 Executive Summary

This project analyzes global food product data to identify underserved opportunities in the "healthy snacking" market. By examining the relationship between sugar and protein content, the analysis reveals a significant gap in high-protein, low-sugar products. While most products are concentrated in high-sugar, low-protein categories, a smaller but valuable segment exists in protein-rich foods such as meat and supplements. This indicates a strong opportunity for companies to innovate healthier snack alternatives that meet modern consumer demand.

---

## 🔗 Project Links

- 📊 **Dashboard (Power BI):**  
  [View Dashboard](https://drive.google.com/file/d/1WsdyAlE35vKip9yf3l9CpF1L8NxlSqQa/view?usp=drive_link)

- 📓 **Notebook (Google Colab / .ipynb):**  
  [View Notebook](https://drive.google.com/file/d/1iQAG03zP4kJi1l7tt8CG0vGzclRLtJ3D/view?usp=drive_link)

- 📄 **Notebook Export (PDF):**  
  [View PDF](https://drive.google.com/file/d/17h-EAMGrcNM5CmzyodKx90JgSdrely_E/view?usp=drive_link)

- 🎥 **Presentation (Slides):**  
  [View Presentation](https://docs.google.com/presentation/d/1FKU3TuJZjCp2MYWhlDTO8wJn7z-K3fYz/edit?usp=sharing&ouid=116576799155137922183&rtpof=true&sd=true)

---

## 🧹 Technical Explanation

### Data Cleaning

The Open Food Facts dataset was large and unstructured, requiring careful preprocessing:

- Loaded a manageable subset (~10,000 rows) for performance
- Removed missing values in key columns:
  - `sugars_100g`
  - `proteins_100g`
  - `product_name`
- Converted nutritional fields to numeric format
- Filtered out unrealistic values (outside 0–100g range)
- Reduced dataset to ~3,000 valid records

---

### Category Engineering

The `categories_tags` column contained messy, multi-value text strings. To make analysis meaningful:

- Parsed category strings
- Created high-level categories:
  - Meat
  - Snacks
  - Protein Products
  - Beverages
  - Dairy
  - Seafood
  - Cereals
  - Sweets
  - Other

This allowed clear segmentation for business insights.

---

### Blue Ocean Definition

A "Blue Ocean" segment was defined based on nutritional thresholds:

- High Protein: **> 18g per 100g**
- Low Sugar: **< 1g per 100g**

This filtering identified **252 products** representing a potential market gap.

---

### Candidate’s Choice (Added Value)

An additional category-level analysis was introduced to identify **which food categories dominate the Blue Ocean space**.

#### Why this matters:
Understanding *which categories already perform well* helps businesses:
- Identify strong benchmarks (e.g., Meat, Protein Products)
- Spot weak categories (e.g., Snacks)
- Target innovation where competition is low

---

## 📊 Key Insights

- Most products are clustered in **high-sugar, low-protein** space
- Only a small segment meets **high-protein, low-sugar** criteria
- **Meat and Protein Products dominate** this healthy segment
- Traditional snack categories are **underdeveloped in health positioning**

---

## 💡 Final Recommendation

Based on the analysis:

> The biggest market opportunity lies in developing high-protein (>18g) and low-sugar (<1g) products, particularly by innovating healthier snack alternatives inspired by protein-rich food categories.

---

## 🚀 Project Value

This project demonstrates how data analysis can:
- Identify hidden market gaps
- Support product innovation strategy
- Transform raw data into actionable business insights
