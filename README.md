# Stock-price-prediction
![Python](https://img.shields.io/badge/Python-3.9-blue?style=flat&logo=python) 
![scikit-learn](https://img.shields.io/badge/scikit--learn-0.24.2-orange?style=flat&logo=scikitlearn)
![pandas](https://img.shields.io/badge/pandas-1.3.3-blue?style=flat&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-1.21.2-013243?style=flat&logo=numpy)
![Neural Networks](https://img.shields.io/badge/Neural%20Networks-Deep%20Learning-blue?style=flat&logo=tensorflow)

A machine learning model that summarizes long text passages using an LSTM-based neural network. Built with TensorFlow on the backend and powered by a modern UI using Next.js and Tailwind CSS. The API layer is handled by Flask, allowing real-time summarization of user input.

## Tech Stack
- ` Python ` : versatile, high-level, interpreted, easy-to-learn programming language.
- ` Scikit-Learn `: A powerful Python library for machine learning.
- ` Numpy `: A powerful Python library for machine learning.
- ` Pandas `: A powerful Python library for machine learning.
- ` Matplotlib `: A powerful Python library for machine learning.
- ` Seaborn `: A powerful Python library for machine learning.



## Getting Started

### 1. Clone the Repository
First, clone the repository to your local machine:


```bash
git clone https://github.com/rahul-shrivastav/NLP-text-summarizer.git
```
### 2. Install Dependencies
Change the directory and Install the required dependencies by running:

```bash
cd NLP-text-summarizer/backend
pip install -r requirements.txt
cd ../frontend
npm install
```

### 3. Setup Environment Variables in Frontend folder

To run this project, you will need to add the following environment variables to your .env file in frontend
```bash
VITE_API
```
A sample .evn file is also provided in the repository.


### 4. Run the application locally

Navigate to `/backend` and run the development backend server :

```bash
python app.py
```
Now navigate to `/frontend` and run the development frontend server :
```bash
npm run dev
```
Open port `5173` on `localhost` with your browser to see the result. 





