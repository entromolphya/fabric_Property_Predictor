# Fabric Property Predictor

A machine learning–based web application designed to predict **Stitch Length (SL)** and **Yarn Count (YC)** for textile fabrics using fabric and machine parameters.

---

## Description

This project provides a predictive system to assist textile engineers in estimating key fabric properties, reducing reliance on manual trials and improving production efficiency. The application uses trained machine learning models and a Streamlit-based interface for interactive use.

---

## Predicted Properties

- Stitch Length for ground yarn  
- Stitch Length for elastane yarn  
- Yarn Count (Ne, Denier, Filament) for ground yarn  
- Yarn Count (Denier) for elastane yarn  

---

## Input Parameters

- Fabric construction type  
- Fiber composition  
- Machine diameter  
- Machine gauge  
- Fabric color category  
- Fabric GSM (weight)

---

## Installation

Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/Fabric_Property_predictor.git
cd Fabric_Property_predictor
````

Create and activate a virtual environment:

```bash
python -m venv venv
source venv/bin/activate   # macOS/Linux
venv\Scripts\activate      # Windows
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run main.py
```

---

## Technologies Used

* Python
* Streamlit
* scikit-learn
* Pandas
* NumPy

---

## Project Structure

```
Fabric_Property_predictor/
├── main.py
├── models/
├── requirements.txt
└── README.md
```

