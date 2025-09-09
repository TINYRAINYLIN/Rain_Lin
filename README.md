                          🎓 Master’s student in Data Science at Boston University with a B.S. in Psychology

## Contact
            📧 Email: rain1128@bu.edu   📱 Phone: (631) 829-1448   🌍New York, NY
🔗 [LinkedIn](https://www.linkedin.com/in/rainlin112802/)
💻 [Github] ()
📄 [Resume] ()


## Project Overview
### Hybrid Ensemble Recommender System | End-to-End Hybrid ML Pipeline 
Links: [GitHub Repo](https://github.com/The-Zero-Shot-Duo/Hybrid-Ensemble-Recommender-System) · [Live Demo](https://huggingface.co/spaces/ZPENG127/Hybrid-Ensemble-Recommender-System)

**Tech Stack:** **Python**, **Pandas**, **scikit-learn**, **Surprise (SVD)**, **PyTorch (NCF)**, **XGBoost**, **Hugging Face**, **NLTK/VADER**, **Streamlit**
- Designed a **multi-stage pipeline** combining **SVD/NCF collaborative filtering**, **BERT content similarity**, and **VADER sentiment** to generate **candidate items and features**.  
- Trained an **XGBoost ranker** to score candidates, reaching **Precision@5 = 0.88**, **Recall@5 = 0.86**, **AUC = 0.89** on the **Amazon Electronics dataset**.  
- Implemented **Neural Collaborative Filtering (NCF)** in **PyTorch** to add a **deep-learning perspective** to collaborative signals.  
- **Deployed a Streamlit app** on **Hugging Face Spaces** for **real-time exploration and evaluation**.

📌 **Status:**  
- Adding **product catalog metadata enrichment** (**titles, images, categories**) and **UI search/filters** so users can browse by **keyword/category** instead of **raw IDs**.

### Zillow Home Value Prediction | End-to-End Regression Pipeline 
Links: [GitHub Repo](https://github.com/TINYRAINYLIN/Zillow_Property_Price_Prediction)

**Tech Stack:** **Python**, **Pandas**, **scikit-learn**, **RandomizedSearchCV/GridSearchCV**, **Ridge**, **Random Forest**, **LightGBM**, **Matplotlib/Seaborn**
- Built a **property-value prediction pipeline** on **Zillow data**: **EDA**, **outlier/missing-value handling**, and **feature engineering**.  
- Trained and compared **Ridge**, **Random Forest**, and **LightGBM** with **cross-validation**, **randomized hyperparameter search**, and **grid search**.  
- Added clear **plots (R²/MAE/RMSE)** and **residual diagnostics** to validate **stability**.  
- **Random Forest delivered the top cross-validated performance (R²≈0.979, MAE≈5,266, RMSE≈87,717).**

📌 **Status:**  
- **Current:** **Hyper-tuning RF & LGBM** and selecting a **champion model** via **CV + test metrics**.  
- **Next:** Add **explainability** (**feature importance → permutation → SHAP**), modularize into **src/** + add **predict.py** and **basic tests**, **deploy Streamlit app**.
