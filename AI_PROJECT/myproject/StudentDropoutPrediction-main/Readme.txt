💡 Simplified Version for Future Use
Instead of the long activation command, you can use this shorter sequence next time:

powershell
# Option 1: Two simple commands
.venv\Scripts\activate
streamlit run main.py

# Option 2: One combined command (Windows)
& .venv\Scripts\Activate.ps1 && streamlit run main.py

# Option 3: Direct Python call
python -m streamlit run main.py  # Works even without activating venv first
🚀 Quick Restart Command
If you need to restart your app after making changes:

powershell
# 1. Press Ctrl+C to stop the current app
# 2. Type this to restart:
streamlit run main.py
Your app is now running at http://localhost:8501 - just open that URL in any web browser to see your student dropout prediction application!