# GameGraph: A Graph-Based Video Game Recommendation System

GameGraph is a Python-based project that recommends new video games by analyzing what games players commonly play together. Instead of relying on genres or critic scores, it leverages co-play patterns to provide more personalized and meaningful recommendations.

## ✨ Features
- **Graph-Based Recommendations**: Uses an undirected graph to model games and their player overlaps.  
- **Multiple Recommendation Modes**:  
  - *Single Game Mode*: Shows top games often played together or exclusively with a chosen title.  
  - *Multiple Games Mode*: Suggests the most connected game(s) based on multiple inputs.  
- **Interactive GUI**: Built with Pygame for intuitive browsing and results.  
- **Custom Dataset**: Based on players’ favorite games collected via Google Sheets (CSV).  

## 🛠️ Tech Stack
- **Python 3.13**
- **Libraries**: `pygame`, `csv`, `dataclasses`, `random`

## 🚀 How to Run
1. Clone the repo and navigate into the project folder.  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
python main.py
