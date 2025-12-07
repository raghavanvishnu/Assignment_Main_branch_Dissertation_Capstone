Capstone Project – JP Morgan Chase Fraud Detection

End-to-End Machine Learning + BI + Deployment Project

📌 Abstract

This Capstone Project focuses on detecting fraudulent transactions using the JP Morgan Chase credit card dataset. The project includes data preprocessing, exploratory data analysis, model development, hyperparameter tuning, and real-time deployment using Streamlit. Additionally, Power BI dashboards provide dynamic visual insights into fraud trends.
All code, reports, presentations, and deployment artifacts are consolidated in this repository.

📚 Table of Contents

Project Notebooks

Capstone Presentation

Power-BI Dashboard

Streamlit Application

Dataset

Tech Stack

How to Run the Project

📝 1. Project Notebooks
a. Main Analysis Notebook

🔗 https://github.com/raghavanvishnu/Assignment_Main_branch_Dissertation_Capstone/blob/main/Capstone_Project_JP_Morgan_Chase_Dataset.ipynb

Contains EDA, preprocessing, model baselines, and fraud pattern analysis.

b. Final Optimized Notebook

🔗 https://github.com/raghavanvishnu/Assignment_Main_branch_Dissertation_Capstone/blob/main/Final_Complete_Capstone_Project_Optimized.ipynb

Includes advanced modeling, CatBoost optimization, hyperparameter tuning, and final evaluation metrics.

📊 2. Capstone Presentation

📄 Final Presentation Deck
🔗 https://github.com/raghavanvishnu/Assignment_Main_branch_Dissertation_Capstone/blob/main/Capstone_Presentation_Final.pptx

Summarizes the entire journey: business goal → methodology → model → insights → deployment.

📈 3. Power BI Dashboard
Power BI Workbook (External Link – Large File)

🔗 https://drive.google.com/file/d/17I4JvBhYs2BSi9sJeQwZIjd1ul_oMuxa/view?usp=drive_link

Power BI Slides (PDF/PPT)

🔗 https://github.com/raghavanvishnu/Assignment_Main_branch_Dissertation_Capstone/blob/main/PowerBI_Slides_Capstone.pptx

Provides visual explanation of fraud trends, KPIs, and anomaly patterns.

🖥️ 4. Streamlit Application
Deployment ZIP Folder

🔗 https://github.com/raghavanvishnu/Assignment_Main_branch_Dissertation_Capstone/blob/main/Capstone_Deployment.zip

A ready-to-run Streamlit web application for real-time fraud prediction.

How to Run the Streamlit App

Download & extract the ZIP file.

Open Visual Studio Code, load the extracted folder.

Open a new terminal.

Install dependencies:

pip install catboost
pip install streamlit joblib pandas numpy


Start the app:

streamlit run app.py


The app opens automatically at localhost:8051.

Copy the first row from Sample_1000_Rows.csv (inside the ZIP).

Click Predict → Model displays Fraud / Not Fraud.

✔️ Ensure Python is installed and added to PATH.

🗂️ 5. Dataset

📁 Original Dataset (Large – Google Drive)
🔗 https://drive.google.com/drive/u/0/folders/1F7Du5Ey0ab9xprD0w_f8-yAbXt_sB8OP

Stored externally due to size limitations.

🧰 6. Tech Stack
Component	Tools Used
Languages	Python (NumPy, Pandas), DAX (Power BI)
ML Models	CatBoost, Random Forest, Logistic Regression
Visualization	Matplotlib, Seaborn, Power BI
Deployment	Streamlit, Joblib
IDE	Jupyter Notebook, VS Code
Version Control	Git & GitHub
🚀 7. How to Run the Project Locally
Clone the Repository
git clone https://github.com/raghavanvishnu/Assignment_Main_branch_Dissertation_Capstone.git

Open Jupyter Notebook
jupyter notebook

Run Power BI Dashboard

Download .pbix → Open using Microsoft Power BI Desktop.

Run the Streamlit App

(As described above)# Capstone Project Dissertation 

This is a readme file that contains details of the various files used for the purposes of the dissertation namely

the final jupyter notebook files uploaded here : https://github.com/raghavanvishnu/Assignment_Main_branch_Dissertation_Capstone/blob/main/Capstone_Project_JP_Morgan_Chase_Dataset.ipynb & https://github.com/raghavanvishnu/Assignment_Main_branch_Dissertation_Capstone/blob/main/Final_Complete_Capstone_Project_Optimized.ipynb

The presentation is a file : https://github.com/raghavanvishnu/Assignment_Main_branch_Dissertation_Capstone/blob/main/Capstone_Presentation_Final.pptx :

This file gives the details regarding the work done in a nutshell.

PoweorBI workbook: this is the powerbI workbook created expalining the dataset and findings- Url for the same is here : https://drive.google.com/file/d/17I4JvBhYs2BSi9sJeQwZIjd1ul_oMuxa/view?usp=drive_link . Stored externally due to file size

PowerBI_Slides_Capstone: https://github.com/raghavanvishnu/Assignment_Main_branch_Dissertation_Capstone/blob/main/PowerBI_Slides_Capstone.pptx

This is the slide explaining the powerbi workbook

the streamlit application : Folder for the same : https://github.com/raghavanvishnu/Assignment_Main_branch_Dissertation_Capstone/blob/main/Capstone_Deployment.zip

How to use the streamlit application 
1. Download the zip file and extract the zip file in easy accessible folder.
2. Open Visual Studio Code
3. Open the Folder where you have extracted the Zip file (Complete Folder name needs to be added here)
4. Open a new terminal (inside the Visual Studio Code)
5. In the terminal, add this command "pip install catboost". It will install after
6. In the same terminal, add this command "pip install streamlit joblib pandas numpy"
7. Now run this command "streamlit run app.py". This will run the Streamlit app in your Browser On port no: localhost:8051.
8. Now you will copy the first row from the Sample 1000 rows csv file, attached in the Zip file. 
9. Then click the 'Predict' button on the Web browser. The output can be displayed as whether the transaction is fraud or not fraud.

Note: Make sure you have Python installed in your Visual Studio Code.


Dataset Used:  https://drive.google.com/drive/u/0/folders/1F7Du5Ey0ab9xprD0w_f8-yAbXt_sB8OP (stored extrenally owing to size)





