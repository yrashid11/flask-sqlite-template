# Flask Template Project

This is a general-purpose Flask template with SQLite integration and file upload support.

## Setup

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python run.py
```

## Upload Endpoint

POST `/upload`

Form-Data: `file=<your_file>`
