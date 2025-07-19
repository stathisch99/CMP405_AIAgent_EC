# 🤖 CMP405_AIAgent_EC

## 📝 Project Title:
**AI Agent / Planning (AI)**

## 🎯 Description:
This project implements an AI-based agent that predicts whether an anime is likely to be in the Top 3000 based on selected attributes (genre, studio, popularity, favorites, members, and episodes).  
It uses a trained XGBoost classifier with a custom threshold to improve high-rank recall.  
A Gradio user interface is built to make real-time predictions based on user input.

## 👨‍🎓 Student Info:
- **Ονοματεπώνυμο (Full Name):** E. Charalambous  
- **Αριθμός Μητρώου (Student ID):** *********

## 🚀 How to Run the Project:
This project uses **Gradio + Google Colab**.  
No installation is required — just follow these steps:

1. Go to [Google Colab](https://colab.research.google.com)
2. Upload the following files from this repo:
   - `anime_predictor_ui_py.py`
   - `model.pkl`
   - `anime_rank_model.pkl`
   - `genre_encoder.pkl`
   - `studio_encoder.pkl`
3. Run the Python script in Colab
4. At the bottom, a public Gradio link will appear
5. Open the link to test the AI agent live 🎌

## 📂 Files in This Repository:
| File | Description |
|------|-------------|
| `anime_predictor_ui_py.py` | Main UI code using Gradio |
| `model.pkl` | Pickled model file |
| `anime_rank_model.pkl` | XGBoost trained classifier |
| `genre_encoder.pkl` | Label encoder for genres |
| `studio_encoder.pkl` | Label encoder for studios |
| `README.md` | This file |

## 💡 Notes:
- The model was trained using a threshold of `0.459` to improve recall for high-ranked anime.
- The interface allows users to select from real genres and studios based on the dataset.
