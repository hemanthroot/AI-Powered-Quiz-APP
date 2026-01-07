# AI-Powered Quiz App

Simple Flask app that generates quizzes using Google GenAI.

Quick start

1. Create and activate a virtual environment (recommended):

```powershell
python -m venv labss
labss\Scripts\activate
```

2. Install dependencies:

```powershell
pip install -r requirements.txt
```

3. Create a `.env` file with your Gemini API key:

```
GENAI_API_KEY=your_api_key_here
```

4. Run the app using the virtualenv Python:

```powershell
labss\Scripts\python.exe main.py
```

Notes

- `.env` is excluded from the repo. Keep secrets out of source control.
- If you prefer using system Python, install dependencies into that environment instead.
