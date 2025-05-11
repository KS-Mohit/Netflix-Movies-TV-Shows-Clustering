Netflix Movies & TV Shows Clustering
This project performs exploratory data analysis (EDA) and clustering on a Netflix dataset to uncover patterns and group similar content. It utilizes machine learning techniques such as KMeans clustering and Principal Component Analysis (PCA) to analyze and visualize the distribution of movies and TV shows.

📁 Dataset
The dataset comprises information about Netflix titles, including attributes like title, type (Movie or TV Show), director, cast, country, date added, release year, rating, duration, genres, and description.

🔍 Project Overview
The analysis is conducted in the Copy_of_ML_EDA&Clustering_Submission.ipynb notebook and includes the following steps:

Data Cleaning: Handling missing values and standardizing data formats.

Feature Engineering: Creating new features such as content duration in minutes and extracting primary genres.

Exploratory Data Analysis (EDA): Visualizing data distributions, trends over years, and country-wise content production.

Clustering: Applying KMeans clustering to group similar content based on selected features.

Dimensionality Reduction: Using PCA to reduce feature dimensions for visualization purposes.

Visualization: Plotting clusters to interpret the grouping of content.

🛠️ Setup Instructions
To run the notebook locally, follow these steps:

Clone the Repository:

bash
Copy
Edit
git clone https://github.com/KS-Mohit/Netflix-Movies-TV-Shows-Clustering.git
cd Netflix-Movies-TV-Shows-Clustering
Install Dependencies:
Ensure you have Python 3.x installed. Install the required libraries using pip:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn
Run the Notebook:
Launch Jupyter Notebook or any compatible environment and open:

Copy
Edit
Copy_of_ML_EDA&Clustering_Submission.ipynb
📊 Results
The clustering analysis groups Netflix content into distinct clusters based on features like type, duration, and release year. The PCA visualization provides insights into how different titles relate to each other in the reduced feature space.

📌 Notes
Ensure that the dataset file is available in the working directory or update the notebook's data loading path accordingly.

The notebook includes detailed comments and explanations for each step, facilitating understanding and reproducibility.

📄 License
This project is open-source and available under the MIT License.
