---

# MasterControl Capstone | Group 6  | Sina Odejinmi



---

## **1. Business Problem**

MasterControl provides quality and manufacturing management software to life sciences organizations, including pharmaceutical, biotechnology, and medical device manufacturers. While the **Quality Solutions (Qx)** product line achieves a strong **19.7%** conversion rate, the newer **Manufacturing Solutions (Mx)** product line converts at only **12.7%**.  

This underperformance limits MasterControl’s ability to allocate sales and marketing resources effectively and slows adoption of the Mx solution. As the company expands Mx into new markets, it lacks clarity on which customer segments are most likely to convert.

---

## **2. Business Objectives**

The primary objective is to increase Mx conversion rates by identifying and prioritizing customer profiles with the highest likelihood of progressing through the sales funnel. Specifically, MasterControl seeks to determine:

- Which **industries, manufacturing models, site functions, and company sizes** align most strongly with Mx  
- Which **job titles, seniority levels, and functional roles** most influence sales progression  
- Which existing **Qx customers** are strong candidates for adopting Mx as an additional solution  

---

## **3. Group Solution Approach**

Our team conducted a comprehensive analysis of the MasterControl dataset to understand the drivers behind Mx underperformance relative to Qx. Through exploratory data analysis (EDA), we identified patterns in the dataset that did not align with the ideal customer profile (ICP) for Mx, as well as the ICP characteristics associated with leads that successfully converted.

We developed predictive models using:

- **Logistic Regression**  
- **Random Forest**  
- **Gradient Boosting Machines**

These models achieved strong AUC performance and enabled us to rank leads by conversion probability. High‑scoring leads were analyzed to extract ICP characteristics, which were then combined with cumulative conversion patterns to identify the segments most likely to progress through the sales funnel.

The resulting ICP insights were translated into actionable recommendations for MasterControl.

---

## **4. Business Value of the Solution**

The modeling framework effectively distinguishes low‑value leads from high‑value opportunities. By assigning a probability score to each lead, MasterControl can:

- Reduce wasted sales effort by deprioritizing leads unlikely to convert  
- Focus resources on high‑scoring leads with strong conversion potential  
- Validate new prospects against data‑driven ICP criteria  
- Improve overall Mx conversion rates through targeted engagement strategies  

The ICP recommendations further support strategic refinement of marketing outreach, sales qualification, and account prioritization.

---

## **5. My Contribution to the Project**

I completed the full EDA and modeling workflow used in the final submission. Although an initial EDA draft was provided, I conducted the full second‑round EDA that informed all subsequent analysis. I also developed and executed all modeling pipelines, including feature engineering, model training, evaluation, and interpretation.

My work focused on understanding the dynamics of Mx sales performance and identifying the ICP characteristics most predictive of conversion.

---

## **6. Challenges Encountered**

The most significant challenge was aligning the team around the analytical approach required to solve the business problem. My methodology focused on linking high‑scoring leads to their ICP attributes, which revealed conversion rates exceeding **46%** within top score percentiles. Although initially counterintuitive to some team members, the data supported this insight. After faculty guidance, the team aligned around the approach.

A second challenge involved troubleshooting and refining the modeling code. Despite AI assistance, achieving a stable, reproducible pipeline required significant iteration, patience, and attention to detail.

---

## **7. What I Learned**

This project reinforced the importance of treating missingness as potentially informative rather than automatically removing it. The EDA process provided critical direction for model development and shaped the solution strategy. I also gained deeper experience in connecting model outputs to business‑relevant insights, particularly in defining and validating ICPs for sales optimization.

---

