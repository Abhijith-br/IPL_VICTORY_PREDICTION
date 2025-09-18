# IPL Victory Predictor

A web app built with **Streamlit** that predicts the winning probability of an IPL (Indian Premier League) match given the current game situation (batting team, bowling team, venue, score details, etc.).

---

## 🎯 Features

- Select batting and bowling teams from dropdown menus
- Choose match venue from a list of cities
- Input current score, overs completed, wickets lost, and target
- Computes:
  - Runs left
  - Balls left
  - Wickets remaining
  - Current run rate (CRR)
  - Required run rate (RRR)
- Displays probabilities of winning and losing for the batting team

---

## 🧰 Tech Stack

- Python 3.x  
- Streamlit for the web UI  
- scikit-learn for machine learning model  
- Pandas for data handling  
- Pickle for model serialization

---

## 🚀 Getting Started

### Prerequisites

- Python 3.7 or higher  
- `pip` package manager

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Abhijith-br/IPL_VICTORY_PREDICTION.git
   cd IPL_VICTORY_PREDICTION

2.Install the required packages:

    pip install -r requirements.txt

    
🧪 How It Works

Loads a trained machine learning pipeline (pipe.pkl) which includes preprocessing and classification model.

Takes input from the user about teams, venue, and match stats.

Calculates derived features such as runs left, balls left, current and required run rates.

Feeds these features into the model to get probabilities of winning and losing.

Displays the prediction probabilities interactively.
