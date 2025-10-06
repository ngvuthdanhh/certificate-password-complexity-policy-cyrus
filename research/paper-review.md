# Research Paper Reviews

## Purpose
This file is used to summarize and critically evaluate research papers, reports, or whitepapers relevant to email security, phishing analysis, and password policy studies.

---

### Template for Each Paper

**Title:**  
**Authors:**  
**Year / Source:**  
**Link:**  

**Summary:**  
- Main problem addressed.  
- Proposed solution or model.  
- Methodology.  
- Key findings.  

**Strengths:**  
- (e.g., Strong dataset, real-world applicability)  

**Weaknesses / Gaps:**  
- (e.g., Limited scope, lack of experimental data)  

**Relevance to Our Project:**  
- How this research helps improve our labs, docs, or training materials.  

---

### Example Entry

**Title:** “Detecting Phishing Emails Using Machine Learning Techniques”  
**Authors:** John Doe, Jane Smith  
**Year / Source:** 2022, IEEE  
**Link:** https://doi.org/xxxx  

**Summary:**  
The paper proposes a machine learning model using Random Forest and SVM to classify phishing vs legitimate emails based on header and body features. Achieved ~95% accuracy on a test dataset.  

**Strengths:**  
- Strong performance metrics.  
- Diverse dataset including multi-language phishing emails.  

**Weaknesses / Gaps:**  
- Limited evaluation of adversarial techniques (e.g., obfuscation, encoding).  
- Dataset not publicly available.  

**Relevance to Our Project:**  
Helps in designing detection labs (`labs/`) and evaluation of filtering rules (`docs/10-mail-server-security.md`).  
