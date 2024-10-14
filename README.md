# Text Classification of Legitimate and Rogue Online Privacy Policies

Welcome to the repository for my **Master Thesis Project** titled **"Text Classification of Legitimate and Rogue Online Privacy Policies: Manual Analysis and a Machine Learning Experimental Approach."**

This project investigates the use of **supervised binary classification** to distinguish between legitimate privacy policies from Fortune Global 500 companies and rogue policies from less trustworthy websites. The repository contains the code, data, and documents used in the thesis work.

## Project Overview

In this project, we evaluate **15 classification algorithms** to determine how well they can differentiate between legitimate and rogue privacy policies. The dataset consists of **100 privacy policies** from legitimate websites (top Fortune Global 500 companies) and **67 privacy policies** from rogue websites. A manual analysis was conducted to measure adherence to **seven general privacy principles**, highlighting significant statistical differences between legitimate and rogue policies. 

Our findings show that privacy policies from legitimate companies have **98% adherence** to the seven privacy principles, compared to only **45% adherence** in rogue companies' policies. After evaluating the classification models, the **Naïve Bayes Multinomial** algorithm exhibited the best performance with an **AUC score of 0.90 (0.08)**, outperforming other candidates in statistical tests.

You can find a more detailed abstract and analysis in the full thesis document, accessible [here](https://www.diva-portal.org/smash/get/diva2:1045553/FULLTEXT02).

## Repository Contents

The repository is organized into the following key components:

1. **Java Code for the Classification Model**  
   The complete Java code used to implement and evaluate the 15 classification algorithms.

2. **Privacy Policies Dataset**  
   A zip file containing the **privacy policies** collected for the project, including both legitimate and rogue policies.
   - File: `policies.zip`

3. **Manual Analysis Dataset**  
   A zip file containing the **manual analysis** of the privacy policies, including the evaluation of the seven privacy principles.
   - File: `manual analysis dataset.zip`

4. **Thesis Document (PDF)**  
   The full thesis document detailing the project, analysis, and results.
   - File: `Master_Thesis_submission.pdf`
   - You can also access it online at [Diva Portal](https://www.diva-portal.org/smash/get/diva2:1045553/FULLTEXT02).

5. **Project Proposal (PDF)**  
   The proposal that was submitted for the approval of the Master Thesis Project.
   - File: `proposal for thesis.pdf`

## How to Cite

### Journal Article
This project was later submitted to a journal. If you would like to cite the **journal article**, please use the following format:

```
Boldt, M. and Rekanar, K., 2019. Analysis and text classification of privacy policies from rogue and top-100 fortune global companies. International Journal of Information Security and Privacy (IJISP), 13(2), pp.47-66.
```

### Master Thesis
If you would like to cite the **thesis** itself, please use the following format:

```
Rekanar, Kaavya. "Text Classification of Legitimate and Rogue online Privacy Policies: Manual Analysis and a Machine Learning Experimental Approach." (2016). 
Available at: https://www.diva-portal.org/smash/get/diva2:1045553/FULLTEXT02
```

## How to Use This Repository

1. **Classification Model**  
   The Java code can be run to replicate the experiments. It implements the binary classification models and evaluation metrics used in the project.
   
2. **Privacy Policies Dataset**  
   The zip file contains the privacy policies dataset that can be used for similar text classification problems.

3. **Manual Analysis**  
   The manual analysis zip file provides insights into how privacy policies were manually evaluated against the seven general privacy principles.

4. **Thesis Document**  
   Read the thesis PDF for a comprehensive explanation of the methodology, experiments, and results.

5. **Project Proposal**  
   The project proposal PDF outlines the original objectives and structure of the Master's thesis.

## Contact

For any questions or further details, please feel free to reach out!

---

Thank you for your interest in this project! We hope the resources provided here will be useful for your research or practical applications in text classification or privacy policy analysis.
