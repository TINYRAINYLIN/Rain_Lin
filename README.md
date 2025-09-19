                          🎓 Master’s student in Data Science at Boston University with a B.S. in Psychology                       


## Contact Info

📧 Email: rain1128@bu.edu 
📱 Phone: (631) 829-1448
🔗 [LinkedIn](https://www.linkedin.com/in/rainlin112802/) 
💻 [Github](https://github.com/TINYRAINYLIN) 
📄 [Resume](https://github.com/TINYRAINYLIN/Rain_Lin/blob/main/RainLin_Resume.pdf)

## Project Overview
#### **Amazon Electronics Recommender System** | End-to-End Hybrid Machine Learning Pipeline 
Links: [GitHub Repo](https://github.com/The-Zero-Shot-Duo/Hybrid-Ensemble-Recommender-System) · [Live Demo](https://huggingface.co/spaces/ZPENG127/Hybrid-Ensemble-Recommender-System)

📌 **Description:**  
- Engineered product candidates using **SVD (collaborative filtering) and BERT content similarity**, and constructed **feature vectors** with prediction scores, sentiment analysis, and metadata to enrich ranking inputs.
- Built a **recommender system ranking pipeline** with XGBoost to generate relevance scores, delivering top recommendations with **Precision@5 = 0.88, Recall@5 = 0.86, and AUC = 0.89**; further boosted performance by ensembling with NCF.
- Deployed an interactive **Streamlit app** with **full MLOps** on **Hugging Face Spaces, reducing latency by 20%** and enabling users to explore electronic product recommendations in real time.

📌 **Tech Stack:** 

- Python, scikit-learn, Surprise, XGBoost, Neural Collaborative Filtering, PyTorch, Hugging Face, NLTK, VADER, Streamlit
![Sentiment Score](https://github.com/TINYRAINYLIN/Rain_Lin/blob/main/images/Sentiment%20Score%20for%20Cleaned%20Data.png)
![](https://github.com/TINYRAINYLIN/Rain_Lin/blob/main/images/Demo1.png)

#### **Real Estate Investment Valuation App** | End-to-End Regression Pipeline 
Links: [GitHub Repo](https://github.com/TINYRAINYLIN/Zillow_Property_Price_Prediction)

📌 **Description:**  

- Processed the Zillow Kaggle dataset with **EDA, missing value handling, and engineered 200+ domain-driven features** to enhance predictive accuracy.
- Trained and tuned regression models (Linear, Ridge, Random Forest, LightGBM) with cross-validation; achieved **best performance with Random Forest (R² = 0.874, MAE = 10.9k, RMSE = 271k, 85% within 10k of actual value)**.
- Integrated **SHAP explainability** (beeswarm, dependence, waterfall) and **Folium geospatial visualizations**; preparing deployment of an interactive **Streamlit app on AWS**.

📌 **Tech Stack:** 

- Python, Pandas, scikit-learn, RandomizedSearchCV/GridSearchCV, Ridge, Random Forest, LightGBM, Matplotlib/Seaborn, SHAP, Folium, AWS

![SHAP](https://github.com/TINYRAINYLIN/Real_Estate_Investment_Valuation_App/blob/main/reports/figures/old_shap_beeswarm.png)
![Heatmap](https://github.com/TINYRAINYLIN/Real_Estate_Investment_Valuation_App/blob/main/reports/figures/Heatmap.png)
