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
- **Engineered product candidate sets** by combining **SVD collaborative filtering** with **BERT-based content similarity**, then constructed **feature vectors** using model **prediction scores**, **VADER sentiment analysis**, and **catalog metadata** (**titles, categories, ratings**) to enrich ranking inputs.  
- **Trained and tuned an XGBoost ranker** to score and rank candidate products, delivering **top-N personalized recommendations** with **15% higher accuracy** than baselines (**Precision@5 = 0.88**, **Recall@5 = 0.86**, **AUC = 0.89**), and compared with **Neural Collaborative Filtering (NCF)** for **ensemble improvements**.  
- Deployed an interactive **Streamlit application** with **end-to-end MLOps integration** on **Hugging Face Spaces**, enabling users to **search, filter, and explore recommendations** in real time.  
📌 **Status:**  
- Adding **product catalog metadata enrichment** (**titles, images, categories**) and **UI search/filters** so users can browse by **keyword/category** instead of **raw IDs**.

📌 **Tech Stack:** 

- Python, Pandas, scikit-learn, Surprise (SVD), PyTorch (NCF), XGBoost, Hugging Face, NLTK/VADER, Streamlit

#### **Zillow Property Value Prediction** | End-to-End Regression Pipeline 
Links: [GitHub Repo](https://github.com/TINYRAINYLIN/Zillow_Property_Price_Prediction)

📌 **Description:**  

- **Processed** the Zillow Kaggle dataset with **EDA**, outlier detection, **missing value imputation**, and **feature engineering** to improve model inputs.  
- **Trained and compared** multiple regression models (**Linear Regression, Ridge, Random Forest, LightGBM**) using **cross-validation** and **randomized/grid search** for hyperparameter tuning.  
- **Achieved top performance** with **Random Forest** (R² ≈ 0.979, MAE ≈ $5,266, RMSE ≈ $87,717) and validated results with residual plots and diagnostic analysis.  

📌 **Status:**  
- **Current:** **Hyper-tuning RF & LGBM** and selecting a **champion model** via **CV + test metrics**.  
- **Next:** Add **explainability** (**feature importance → permutation → SHAP**), modularize into **src/** + add **predict.py** and **basic tests**, **deploy Streamlit app**.

📌 **Tech Stack:** 

- Python, Pandas, scikit-learn, RandomizedSearchCV/GridSearchCV, Ridge, Random Forest, LightGBM, Matplotlib/Seaborn
