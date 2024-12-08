
# **Movie Recommendation System**

A Python-based movie recommendation system that suggests movies similar to the user's choice. The system provides a list of recommended movies along with their posters, creating an interactive and visually appealing experience.

## **Features**
- Recommends 5 movies similar to the selected movie.
- Displays movie posters fetched dynamically using the TMDb API.
- User-friendly interface built with Streamlit.
- Leverages machine learning for similarity-based recommendations.

---

## **How It Works**
1. **Input Selection**: The user selects a movie from a dropdown menu.
2. **Recommendation Logic**:
   - A pre-computed similarity matrix identifies the top 5 most similar movies.
3. **Poster Retrieval**: The TMDb API fetches posters for the recommended movies.
4. **Output**: The recommended movie titles and posters are displayed in a grid layout.

---

## **Technologies Used**
- **Programming Language**: Python
- **Framework**: Streamlit
- **Libraries**:
  - Pandas
  - NumPy
  - Pickle
  - Requests
- **API**: [The Movie Database (TMDb)](https://www.themoviedb.org/)
  
---

## **Setup Instructions**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-recommendation-system.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Download the pre-trained models:
   - Place `movie_list.pkl` and `similarity.pkl` in the `model` folder.
4. Run the Streamlit app:
   ```bash
   streamlit run UserInterface.py
   ```
5. Access the application in your browser at `http://localhost:8501`.

---

## **Demo**
Here’s how the application works:
1. Select a movie from the dropdown.
2. Click **Show Recommendation** to see the top 5 recommended movies.
3. The application displays titles and posters in a clean layout.

---

## **Screenshots**
### User Interface:
![UI Example](https://via.placeholder.com/800x400?text=Add+Screenshots+Here)

---

## **Future Improvements**
- Add user ratings to enhance recommendations.
- Implement genre-based or actor-based filtering.
- Optimize the similarity computation for better accuracy.
- Deploy the application online for easy access.

---

## **Acknowledgments**
- [TMDb API](https://www.themoviedb.org/) for movie data and poster retrieval.
- **Streamlit** for the easy-to-build UI framework.

---

## **License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
