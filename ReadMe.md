# 🚆 NeuroRail – Smart Railway Surveillance

AI-powered system to detect unattended baggage using YOLOv8.

## 🔍 Features
- Person & bag detection
- Real-time tracking

## 🧠 Model
- YOLOv8 trained on custom dataset
- Classes: person, bag, obstacle

## 🚀 How to Run

```bash
pip install -r requirements.txt

# NeuroRail ML Project

## Setup

1. Clone the repo:
git clone https://github.com/priyamredker/NeuroRailML.git

2. Install dependencies:
pip install ultralytics

3. Run notebook:
open notebooks/NeuroRail.ipynb

## Notes
- Models (.pt) are not included
- Place trained model inside /models/
- Dataset is already included

## Structure
datasets/ → training data  
models/ → trained models  
notebooks/ → main code  
videos/ → input videos  
