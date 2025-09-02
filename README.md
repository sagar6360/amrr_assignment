# AMRR TechSols Backend Assignment

This project implements a FastAPI backend with three APIs:
- List Users: `/users`
- Update Wallet: `/update_wallet/{user_id}`
- Fetch Transactions: `/transactions/{user_id}`

To run:
1. Install Python, FastAPI, and Uvicorn.
2. Run `uvicorn main:app --reload`.
3. Test APIs at `http://127.0.0.1:8000/docs`.
