# Retail Sales Analysis and Dashboard Project (Group 6)
Contains files related to Retail Sales Analysis and showing interactive dashboard using Python (Pandas, Numpy, Matplotlib, Plotly Dash) in Colab Notebook. This project is part of NPowerCanada's Junior Data Analyst program showcasing skills learned from the IBM Data Analyst course in Coursera.

🎯 Objective

In this project, we selected a dataset from Kaggle, clean and prepare it (data wrangling), perform exploratory data analysis (EDA), and finally build an interactive dashboard using Python. This mirrors a real job workflow used by Data Analysts and Business Intelligence professionals.

🧩 Dataset Selection

The dataset source is from Kaggle. It is the Retail Sales Dataset made by Mohammad Talib. The following link takes you to the Kaggle page of this dataset:
https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset

📁 File Descriptions

* Group 6 Report on Data Analytics Project Activity.pdf
  * This PDF file contains our final report of the project reporting on Dataset Chosen, Key Insights, Challenges Faced and What We Learned
* Group 6 Static Dashboard View.pdf
  * This PDF file contains screenshots of the Retail Sales dashboard
* Group6_Course8Project_FromRawDataToInteractiveDashboard.ipynb
  * This IPYNB file was exported from Google Colab Notebooks. This notebook file contains all the codes that follows the project steps in data analysis and dashboard creation. The project steps includes:
    * Step 1: Dataset Selection
    * Step 2: Data Wrangling (Cleaning and Preparation)
    * Step 3: Exploratory Data Analysis (EDA)
    * Step 4: Build Interactive Dashboard

🐍 Instructions: Running dashboard to a website using NGROK

- Before August 1, 2026
  - By default, the IPYNB file is set up to use an NGROK Authtoken from an account to run the dashboard to a website. The token string is stored in Google Colab's Secrets. We assume the notebook file does not automatically enable the access to this Secret, but its not, simply enable the access if there is a prompt when running the cell that contains the NGROK code.

- After August 1, 2026
  - After this date, the NGROK Authtoken will no longer be valid. But this can be fixed by simply making your own NGROK account and copying your own token to Google Colab Secrets. Here are the steps:
    1. Go to the NGROK website at https://ngrok.com/
    2. Create your own account if you don't have one
    3. Once logged in, click on 'Your Authtoken' on the left-hand menu to view your unique token
    4. Copy the authtoken string provided on the page
    5. Now go back to the Google Colab Notebook, on the left-hand menu, there is a 'Key' icon, this is the Secrets section
    6. In this section, there should already be a secret named 'NGROK_AUTH_TOKEN', if there is none, create a secret with that name
    7. Still in Secrets, paste the value of the authtoken from NGROK to the value of this 'NGROK_AUTH_TOKEN' secret
    8. Once done, you can run the Google Colab Notebook cell that contains the NGROK code
    9. This specific cell will keep running to host the dashboard in a website
    10. The dashboard website link will be printed in the cell prompt when its running
