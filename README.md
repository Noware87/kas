# Bitget Webhook Bot

En Python Flask-app som tar emot webhook-signaler från TradingView och utför köp/sälj-order via Bitget API.

## Filer
- `app.py`: Huvudlogik för att ta emot webhook och placera order.
- `requirements.txt`: Nödvändiga Python-paket för Render.
- `.gitignore`: Utesluter onödiga filer vid uppladdning till GitHub.

## Miljövariabler (Render > Environment)
- `BITGET_API_KEY`
- `BITGET_API_SECRET`
- `BITGET_API_PASSPHRASE`
