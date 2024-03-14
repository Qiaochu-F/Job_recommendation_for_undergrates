Description
This project aims to provide job recommendations to undergraduates based on different scoring matrices. It employs various algorithms including Analytic Hierarchy Process (AHP), K-Means clustering, decision trees, collaborative filtering, and matrix factorization to deliver personalized recommendations.

Installation
You can open all ipynb files in your Jupyter Notebook. Ensure that Python and Jupyter Notebook are installed on your system.

## Usage

The job recommendation system utilizes a combination of algorithms to provide recommendations:

- **AHP with Improved Calculation Method**: Handles inconsistency in user-provided comparison matrices by using the ratio of student ratings on factors to create a comparison matrix. The calculated weights are then applied to job selection scores.
  
- **K-Means Clustering**: Simulates feedback data from job search websites to cluster the best job options for users.

- **Decision Trees and Collaborative Filtering**: Used when multiple user historical data are available to extract user relevance and job relevance information from AHP score data.

- **Matrix Factorization Algorithms**: Employed when the user rating matrix is highly sparse, such as in scenarios where user privacy concerns limit access to user preferences or job evaluations.

Each part's code, data, and outcomes are available in the "data_and_code" file. Follow the readme in each file.
