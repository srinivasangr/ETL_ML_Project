# Student Exam Performance Indicator

## Project Overview
This project is an end-to-end machine learning pipeline that predicts students' math scores based on various features such as gender, ethnicity, parental education level, lunch type, and test preparation course. The project includes data exploration, model training, and deployment using Flask.

---

## Project Structure
```
ETL_Project/
├── notebook/
│   ├── 1. EDA STUDENT PERFORMANCE.ipynb
│   ├── 2. MODEL TRAINING.ipynb
├── src/
│   ├── pipeline/
│   │   ├── predict_pipeline.py
│   │   ├── train_pipeline.py
├── templates/
│   ├── index.html
│   ├── home.html
├── data/
│   ├── stud.csv
├── application.py
├── app.py
├── Dockerfile
├── requirements.txt
├── README.md
```

---

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/ETL_ML_Project.git
cd ETL_Project
```

### 2. Create a Virtual Environment
```bash
python -m venv venv
```

### 3. Activate the Virtual Environment
- On Windows:
    ```bash
    .\venv\Scripts\activate
    ```
- On macOS/Linux:
    ```bash
    source venv/bin/activate
    ```

### 4. Install Dependencies
```bash
pip install -r requirements.txt
```

### 5. Run the Application
```bash
python app.py
```

---

## Flow Diagram

```plaintext
+-------------------+       +-------------------+       +-------------------+
|   Data Collection | --->  | Exploratory Data  | --->  | Model Training    |
|                   |       | Analysis (EDA)   |       |                   |
+-------------------+       +-------------------+       +-------------------+
        |                           |                           |
        v                           v                           v
+-------------------+       +-------------------+       +-------------------+
|   Feature         | --->  | Model Evaluation  | --->  | Deployment        |
|   Engineering     |       | and Selection     |       |                   |
+-------------------+       +-------------------+       +-------------------+
```

---

## Features
- **Data Exploration**: Analyze the dataset and visualize trends.
- **Model Training**: Train multiple regression models and evaluate their performance.
- **Deployment**: Deploy the best model using Flask for real-time predictions.

---

## Technologies Used
- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn, XGBoost, CatBoost
- Flask
- Docker

---

## Author
Your Name  
[Your GitHub Profile](https://github.com/srinivasangr)

---

## License
This project is licensed under the MIT License.


#End to End  ML project
