
# AI Learning Intelligence Tool

## What this tool does
This is a production-style AI tool that predicts course completion, detects early dropout risk,
and generates human-readable insights for mentors and admins.

## How to run
```bash
pip install -r requirements.txt
uvicorn app.main:app --reload
```

Open: http://127.0.0.1:8000/docs

## Input
JSON payload via POST /predict

## Output
Prediction, risk score, and insights

## Model
Logistic Regression trained offline and loaded during inference.

## AI Usage Disclosure
ChatGPT was used for architecture guidance and documentation support.
All ML logic, model training, and API implementation were independently verified.
