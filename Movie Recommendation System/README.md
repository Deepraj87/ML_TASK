# 🎬 Movie Recommendation System Using Cosine Similarity
Welcome to the Movie Recommendation System! This project suggests a list of movies based on a given movie title using cosine similarity and displays the posters of the recommended movies. Whether you're a movie enthusiast or a data science aficionado, this project will pique your interest!

## 🌟 Project Overview
With an ever-increasing amount of content available on streaming platforms and other media sources, users often find it challenging to decide what to watch next. Our project aims to alleviate this problem by building a recommendation system using the TMDB 5000 movie dataset and evaluating its performance with machine learning metrics.

## 🚀 Features
- 🔍 Personalized Movie Suggestions: Get movie recommendations based on your input title.
- 🎨 Visual Appeal: See posters of the recommended movies.
- 🧠 Smart Recommendations: Uses cosine similarity for accurate and relevant movie suggestions.

## 📁 Dataset
We utilize the TMDB 5000 movie dataset, focusing on the 'title' attribute to generate recommendations.

## 📈 Approach
- **Data Preprocessing:** Load and preprocess the dataset to handle missing values and prepare the data for analysis.
- **Feature Extraction:** Use TF-IDF Vectorizer to transform movie titles into numerical feature vectors.
- **Similarity Computation:** Compute cosine similarity between movie titles to identify similar movies.
- **Recommendation Generation:** Develop a function to generate a list of recommended movies based on cosine similarity scores.
- **Model Evaluation:** Evaluate the performance of the recommendation system using classification metrics.
- **Web Application:** Create a Streamlit web app to interact with the recommendation system and display movie posters.

## 🛠️ Getting Started
### Prerequisites
Ensure you have the following installed:

Python 3.7+
Git
pip
### Installation
**1. Clone the repository**

```bash
 git clone https://github.com/Deepraj87/ML_TASKS.git
```
**2. Install the dependencies**

```bash
pip install -r requirements.txt
```
**3. Get a TMDB API Key**

Sign up at TMDB to get an API key and replace 'YOUR_TMDB_API_KEY' in the app.py file with your actual API key.


## 🎮 Usage
Run the Streamlit application locally:
```bash
streamlit run app.py
```

This will start a local web server and open the Streamlit application in your browser. Enter a movie title and enjoy the personalized recommendations along with their posters.

## 🚀 Deployment
### Deploying on Streamlit Community Cloud:
  **1. Push to GitHub**
```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/Deepraj87/ML_TASKS.git
git push -u origin main
```
**2. Deploy on Streamlit Community Cloud**

- Go to Streamlit Community Cloud and log in with your GitHub account.
- Click on the "New app" button.
- Connect your GitHub repository.
- Select the repository and branch you want to deploy.
- Set the main file path to app.py.
- Click "Deploy".

### Deploying on Render

**1. Push Your Code to GitHub**

If you haven't already, push your code to GitHub:


```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/Deepraj87/ML_TASKS.git
git push -u origin main
```

**2. Create an Account on Render**

Go to Render and create an account if you don't have one.

**3. Create a New Web Service**

- After logging in, click the "New +" button and select "Web Service".
- Connect your GitHub account and authorize Render to access your repositories.
- Select the repository containing your Streamlit app.

**4. Configure the Web Service**

- Name: Give your service a name.
- Branch: Select the branch to deploy (e.g., master).
- Build Command: Render automatically detects Python projects. If needed, you can specify pip install -r requirements.txt.
- Start Command: Specify the command to run your Streamlit app:


```bash
streamlit run app.py --server.port $PORT
```

- Region: Choose a region close to your target audience.
- Instance Type: Choose an instance type. For a simple Streamlit app, the default instance is usually sufficient.
**5. Deploy**

Click "Create Web Service". Render will start building your application. Once the build is complete, your Streamlit app will be live and accessible via the URL provided by Render.

## 🌐 Demo

- Click the link to explore the project:https://movie-recom-cktl.onrender.com
  

## 🤝 Contributing
We welcome contributions! If you have any suggestions, improvements, or bug fixes, please open an issue or submit a pull request.


## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.











