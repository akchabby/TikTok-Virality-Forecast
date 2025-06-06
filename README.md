# TikTok Virality Forecast  
*Can we predict what goes viral before it blows up?*
<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 14 14" id="Tiktok--Streamline-Flex" height="14" width="14">
  <desc>
  </desc>
  <g id="tiktok">
    <path id="Subtract" fill="#000000" fill-rule="evenodd" d="M3.65727 0.474686C4.73112 0.35499 5.85168 0.25 7 0.25s2.26888 0.10499 3.3427 0.224686c1.672 0.186363 3.0154 1.528614 3.1946 3.203594 0.1143 1.0683 0.2127 2.18136 0.2127 3.32172 0 1.14035 -0.0984 2.25341 -0.2127 3.3217 -0.1792 1.675 -1.5226 3.0173 -3.1946 3.2036C9.26888 13.645 8.14832 13.75 7 13.75c-1.14832 0 -2.26888 -0.105 -3.34273 -0.2247C1.98532 13.339 0.641908 11.9967 0.462704 10.3217 0.348408 9.25341 0.25 8.14035 0.25 7c0 -1.14036 0.098408 -2.25342 0.212704 -3.32172C0.641907 2.0033 1.98532 0.661049 3.65727 0.474686ZM8.33196 2.88158c-0.07199 -0.30933 -0.36451 -0.51549 -0.68003 -0.47927 -0.31552 0.03623 -0.55371 0.30333 -0.55371 0.62092v5.7767c0 0.8571 -0.69482 1.55187 -1.55192 1.55187s-1.55192 -0.69477 -1.55192 -1.55187c0 -0.8571 0.69482 -1.55192 1.55192 -1.55192 0.34518 0 0.625 -0.27982 0.625 -0.625s-0.27982 -0.625 -0.625 -0.625c-1.54745 0 -2.80192 1.25446 -2.80192 2.80192 0 1.54747 1.25447 2.80187 2.80192 2.80187 1.54746 0 2.80192 -1.2544 2.80192 -2.80187v-3.489c0.60063 0.50936 1.37344 0.78914 2.28188 0.78914 0.3452 0 0.625 -0.27982 0.625 -0.625s-0.2798 -0.625 -0.625 -0.625c-0.66013 0 -1.15085 -0.20396 -1.51126 -0.52541 -0.36769 -0.32795 -0.64091 -0.81582 -0.78688 -1.44308Z" clip-rule="evenodd" stroke-width="1"></path>
  </g>
</svg> 


![TikTok banner](https://media.giphy.com/media/l0MYt5jPR6QX5pnqM/giphy.gif) <!-- replace with your own banner if you have one -->

## Overview  
This project analyzes TikTok video metadata to uncover patterns behind viral content.  
Using natural language processing (NLP), time-based trends, and machine learning classification, I built a predictive model that answers:

 **"Will this TikTok go viral?"**

---

## Problem Statement  
TikTok is notoriously unpredictable — but can data reveal the secrets behind virality?

We explore:
- 🔠 Do specific hashtags or caption tones influence engagement?
- ⏰ Does upload time affect views?
- 🎧 Do certain sounds drive trends?
- 🧠 Can we predict virality using a model trained on real-world videos?

---

## Dataset  
Source: [Kaggle TikTok Dataset (2022-2023)](https://www.kaggle.com/datasets/advaypatil/tiktok-dataset)  
- 50,000+ public TikToks  
- Columns: `video_id`, `likes`, `shares`, `views`, `hashtags`, `caption`, `sound_title`, `upload_time`, `length`  
- Binary `is_viral` flag for classification

---

## Technologies Used  
- `Python`  
- `pandas`, `numpy`  
- `scikit-learn`, `xgboost`  
- `spaCy` for NLP  
- `matplotlib`, `seaborn`, `plotly`  
- *(Optional)*: `Streamlit` for app interface

---

## Project Structure
tiktok-virality-forecast/
│
├── data/ # Raw and cleaned datasets
├── notebooks/ # Jupyter Notebooks for EDA and modeling
├── models/ # Saved ML models
├── app/ # Streamlit/Dash app (optional)
├── README.md
├── requirements.txt
└── .gitattributes # For GitHub language override


---

## Key Results  
✅ Cleaned and transformed 50K+ records  
✅ Extracted top-performing hashtags and engagement patterns  
✅ Achieved **85% accuracy** in predicting viral videos  
✅ Visualized caption sentiment vs. video success  

---

## Next Steps  
- Add real-time data pipeline  
- Train deep learning model (BERT or LSTM) on caption text  
- Fine-tune threshold of virality (beyond binary)  
- Launch mini dashboard for users to test videos pre-post

---

## Demo  
(*Coming soon*) A dashboard where users paste in a TikTok link or caption and see the virality forecast.

---

## Author Insight  
Data is never neutral. This project doesn't just look at views — it challenges what it means to "go viral" and how social media manipulates our attention.

---




