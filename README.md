# Anime Dataset
This repository contains a JSON dataset of anime details fetched using the AniList API.

## Dataset
- `anime_list.json`: A JSON file containing anime details, including:
  - Titles (English and Romaji)
  - Genres
  - Episodes
  - Average Score
  - Studios
  - Start and End Dates
  - Season
  - Status
  - Description
  - Main and Supporting Characters

## Usage
You can load the dataset using Python:
```python
import json

with open('anime_list.json', 'r', encoding='utf-8') as file:
    data = json.load(file)
    print(data)
