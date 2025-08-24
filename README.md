# Telegram Bot on Render

This is a simple Telegram bot deployed on Render.

## Files
- `bot.py` → Main bot script
- `requirements.txt` → Python dependencies
- `Procfile` → Tells Render to run `python bot.py`
- `runtime.txt` → Locks Python version to 3.11.9
- `README.md` → Project info

## Deploy Steps
1. Upload code to GitHub
2. Connect GitHub repo to Render
3. Deploy as Worker service
4. Add your bot token in Render Environment Variables
