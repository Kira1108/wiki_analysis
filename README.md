# wiki_analysis

Predict wikipedia article type.

### Start Application
```bash
uvicorn main:app --reload
```

### Send Request
```bash
POST: http://127.0.0.1:8000/text/nb

{"texts": ["math if hard to learn",
"This is a computer game","This music sounds good",
"football is a great game","my cells pains"]}
```
