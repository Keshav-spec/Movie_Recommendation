
# Movie Recommendation System


## Overview

The Movie Recommendation System is a machine learning-driven web application that suggests movies tailored to user preferences. Built using Python and hosted locally, this platform leverages similarity algorithms to generate personalized movie recommendations from a comprehensive dataset of popular films.

### Features

- Personalized Recommendations: Provides movie suggestions based on similarity to user-inputted preferences.
- Efficient Computation: Precomputed similarity scores allow for quick and responsive recommendations.
- User-Friendly Web Interface: Simple, intuitive design for easy exploration and discovery of movie options.

### Project Structure
- app.py: Core application script managing server-side operations and rendering movie recommendations.
- artifact/similarity1.pkl: Contains precomputed similarity values based on the dataset for efficient recommendation retrieval.
- static/: Directory housing CSS, JavaScript, and other static assets for front-end styling and interaction.
- templates/: HTML templates used to structure and style web pages.
### Dataset
This recommendation system is powered by a rich dataset featuring:

- Title and Genre Information
- User Ratings: Scores based on user feedback
- Popularity Metrics: Indicators of movie popularity based on views or external ratings
The dataset is preprocessed, with similarity values stored in ```similarity1.pkl``` to improve performance in generating recommendations.

### Getting Started
#### Prerequisites
- Python: Ensure Python 3.x is installed.
- Git LFS (Large File Storage): Used to manage large files in the repository. Set up Git LFS to avoid issues when working with large files like ```similarity1.pkl```.
### Installation
- Clone the repository

```bash
git clone https://github.com/Keshav-spec/Movie_Recommendation.git
cd Movie_Recommendation
```


- Install Dependencies: Install required packages listed in ```requirements.txt```.
```bash
pip install -r requirements.txt
```
- Run the Application: Start the local server to host the website.

```bash
python app.py
```
The application will be available at ``` http://localhost:5000.```

### Troubleshooting
#### Common Issues
- Large File Management: If issues arise with large files, ensure you’ve set up Git LFS:
``` bash 
git lfs install
```
### Future Improvements
The project is actively evolving, and future updates may include:

- Enhanced Recommendation Algorithms: Potential use of collaborative filtering or deep learning models.
- Improved UI/UX: Further refining the interface for an optimal user experience.
- Expanded Dataset: Incorporating additional data points for more precise recommendations.
Contributing
Contributions are welcome! Please submit pull requests or open issues to report bugs, request features, or share feedback.

### License
This project is open-source and available under the MIT License.
