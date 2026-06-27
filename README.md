# Business Analytics Internship Assignment – Indian Company Data Enrichment

## 📌 Project Overview

This project was completed as part of a **Business Analytics Internship Assignment**. The objective was to process a large company dataset, identify Indian companies, enrich their business information using publicly available sources, and select the most complete company profiles.

The workflow involved cleaning the dataset, filtering Indian companies, adding additional business-related columns, enriching company information with the help of **Claude Web Search**, and selecting the **Top 25 companies** with the highest data completeness (fewest missing values).

---

## 🎯 Objectives

* Process a large company dataset.
* Clean and preprocess the data.
* Filter companies located in India.
* Create additional business information fields.
* Enrich company profiles using publicly available web information.
* Measure data completeness.
* Select the Top 25 companies with the least missing values.
* Export the final submission dataset.

---

## 📂 Dataset

**Source:** Kaggle Company Dataset

The original dataset contains millions of company records. This project focuses only on companies located in India.

---

## 🛠️ Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Requests
* BeautifulSoup
* KaggleHub
* Claude Web Search
* CSV

---

## 📋 Project Workflow

### Step 1 – Download Dataset

* Downloaded the company dataset from Kaggle.
* Loaded the dataset into Google Colab.

---

### Step 2 – Data Cleaning

Performed several preprocessing tasks, including:

* Removing duplicate records
* Handling missing values
* Cleaning inconsistent data
* Standardizing company information

---

### Step 3 – Filter Indian Companies

Filtered the dataset to retain only companies located in India.

Output:

* `filtered_indian_companies.csv`

---

### Step 4 – Create Enrichment Template

Created a sample output file and added additional columns required for business profiling.

Examples of added columns include:

* Company Description
* Industry
* Headquarters
* Founded Year
* Company Size
* Revenue
* Website
* LinkedIn Profile
* Contact Information
* Social Media Links
* Products/Services
* Other business-related attributes

---

### Step 5 – Data Enrichment

Each company profile was enriched using **Claude Web Search** by collecting publicly available information from official company websites and other reliable online sources.

This step significantly improved the completeness of the dataset by filling previously missing information.

---

### Step 6 – Data Completeness Evaluation

After enrichment, each company record was evaluated based on the number of populated fields.

The completeness of every profile was compared by counting missing (null) values.

---

### Step 7 – Final Company Selection

The **Top 25 companies** with the **fewest missing values** were selected as the final submission.

Output:

* `final_submission.csv`

---

## 📁 Project Structure

```
Business-Analytics-Assignment/
│
├── Untitled-2.ipynb
├── filtered_indian_companies.csv
├── sample_output.csv
├── completed_submission.csv
├── final_submission.csv
├── README.md
```

---

## ▶️ How to Run

Clone the repository

```bash
git clone https://github.com/your-username/business-analytics-assignment.git
```

Install dependencies

```bash
pip install pandas numpy requests beautifulsoup4 kagglehub
```

Open the notebook

```bash
jupyter notebook Untitled-2.ipynb
```

or upload the notebook to **Google Colab** and run all cells.

---

## 📊 Outputs

The project generates the following outputs:

* Cleaned company dataset
* Filtered Indian companies
* Enriched company profiles
* Data completeness evaluation
* Final Top 25 company dataset

---

## ✨ Key Features

* Large-scale data preprocessing
* Data cleaning and transformation
* Indian company filtering
* Business data enrichment
* Public web information collection
* Data completeness assessment
* Selection of the most complete company records
* CSV export for final submission

---

## 🚀 Future Improvements

* Automate web data enrichment using APIs.
* Integrate LinkedIn and Crunchbase data where available.
* Build a dashboard using Power BI or Streamlit.
* Add machine learning techniques for company classification.
* Automate periodic updates to company information.

---

## 👩‍💻 Author

**Ankita Dey**

Business Analytics | Data Analytics | Python | SQL | Power BI

---

## 📄 License

This project was developed for educational and internship assignment purposes.
