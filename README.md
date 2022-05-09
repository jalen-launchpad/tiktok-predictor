# TikTok predictor
The TikTok predictor is a web application that uses the Distant Viewing Toolkit in order to analyze and make predictions on TikTok video success.

The DVT is too large to run this on Heroku, so must be run locally.

## How to download requirements

Run in the terminal:
```
git clone https://github.com/jalen-launchpad/seniorproj.git
```
```
pip install -r requirements.txt
```
## How to run the application

```RUN FLASK_APP=src/upload.py flask run``` from top-level directory

Navigate to https://localhost:5000

If seniorproject.db is not initialized... run these two commance  in terminal
```cp scripts/init_db.py init_db.py```
```python3 init_db.py```

init_db.py needs to be in top-level directory to work.

Link to zip file with 250 training data example videos and metadata.csv: 
https://drive.google.com/file/d/1WdaBDvedAzgIQVqBxnO833ythGYuyj5q/view?usp=sharing
