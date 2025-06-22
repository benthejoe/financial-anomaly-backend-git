
# Financial Anomaly Detection Backend

This is a simple Flask API that simulates financial transaction anomaly detection. It powers the frontend anomaly dashboard.

## API Endpoint

- `GET /anomalies` — returns random transaction data and flags anomalies.

## Local Development

```bash
pip install -r requirements.txt
python app.py
```

## Deployment

1. Push this repo to GitHub
2. Connect it to [Vercel](https://vercel.com)
3. Vercel will auto-detect and deploy using `vercel.json`
