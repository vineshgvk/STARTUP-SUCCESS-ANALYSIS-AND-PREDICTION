
# Startup Success Analysis and Prediction

## Summary

Startups often face challenges in securing funding, a pivotal factor determining their success or failure. Understanding investment rounds, capital utilization, investor profiles, and location-based impacts is crucial. This project delves into startup data, focusing on funding, acquisitions, and investor relationships. With datasets comprising over 60k companies, our analysis aims to extract key insights, predict market readiness, and identify pathways to success.

## Project Goals

1. **Funding Distribution:** Analyze funding trends over time.

2. **Top Funded Companies:** Identify companies with substantial funding. 

3. **Industry-Location Feasibility:** Establish industry-location relationships.

4. **Investment Firms:** Spotlight investment companies fostering startup growth.

5. **Funding Round Analysis:** Examine funding sources like venture capital.

6. **Acquisitions:** Investigate significant acquisitions and their impact.

7. **Time to Acquisition:** Determine the duration for startups to be acquired.

## Methods

We employed data tidying, transformation, visualization, and modeling techniques to achieve our goals. The CAT Boost algorithm with oversampling proved most effective, achieving 76.4% accuracy and 75.8% AUC score.

## Results

- **Top Funded Categories:**

  - Biotechnology, Clean Technology, and E-commerce led in funding.

- **Key Regions:**

  - Specific cities emerged as hubs for these categories.

- **Predictive Model:**

   - Classification models were built to predict the operational status of a startup (operating, acquired, closed, IPO). The target variable was imbalance, so resampling techniques were used.

    - The following models were evaluated:

       - Random Forest
       - CatBoost with undersampling
       - CatBoost with oversampling
   Model evaluation metrics included AUC ROC, accuracy, precision, recall, and F1 score.
    - CAT Boost with oversampling achieved 76.4% accuracy and 75.8% AUC score.

## Discussion 

This project aids aspiring startups in gauging success factors, emphasizing location and funding accessibility. Continuous data integration and transforming the model into a user-friendly website can enhance its utility.

## Prerequisites

- Python 3.x
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- CatBoost
- Imblearn

## Technologies Used

- Python
- Pandas, NumPy, Matplotlib, Seaborn for EDA
- Scikit-learn for modeling
- CatBoost for modeling 
- Imblearn for resampling
- Jupyter Notebook



## Statement of Contributions

This project was a collaborative effort with equal contributions from all team members. Major contributions:



- **Vinesh Kumar Gande:** Data Cleaning, Model Building, EDA
- **Nikhileshwar Reddy Bommareddy:** Data Cleaning, Model Building, EDA

- **Lahari Boni:** Data Cleaning, EDA, Reporting

- **Sai Akhil Rayapudi:** Data Cleaning, Reporting, Model Building

## References


- **FIPS Data:** http://efele.net/maps/fips-10/data/

## Contact

For any queries or interested in contributing to the project further, please feel free to reach out at gande.vi@northeastern.edu.
