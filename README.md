# 🎬 MovieBot – AI Movie Recommendation Chatbot

**MovieBot** is a smart movie recommendation chatbot built using Python and Machine Learning.  
It can understand user input (like "Suggest a Tamil horror movie on Netflix") and respond with matching movie suggestions based on genre, language, platform, and more.

## 💡 Features
- Natural language understanding using trained intent classifier
- Genre, language, actor, year, platform-based filtering
- Uses `genre.json'`,`language.json`,`platform.json` with complete categorized movie data
- Fast and accurate movie suggestions
- Easy to expand for new platforms or genres

## 🛠 Technologies Used
- Python
- Scikit-learn
- TF-IDF Vectorizer
- JSON for movie database
- Custom intent recognition logic

## 📁 Project Structure
- `movie_loader.py`: Core chatbot logic with filters
- `genre.json'`,`language.json`,`platform.json`: Data files for intents and movie database
- `genre_model.py`, `language_model.py`, `platform_model.py`: Classifier files

## 🚀 How to Run
```bash
python `genre_model.py`, `language_model.py`, `platform_model.py`
python movie_loader.py

