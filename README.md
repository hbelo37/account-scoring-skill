# 🚀 Account Scoring Skill

A lightweight ICP-based account scoring engine that ranks companies based on similarity to your best customers.

## Features

- Train ICP from existing customers
- Score new accounts (0–100)
- Feature-level breakdown
- Fit classification (High / Medium / Low)
- API-first design (FastAPI)

## Endpoints

### Train ICP
`POST /train_icp`

### Score Accounts
`POST /score_accounts`

## Run locally

```bash
pip install -r requirements.txt
uvicorn app:app --reload
