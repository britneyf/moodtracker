# Mood Tracker

This notebook-based tool allows our patient support team to log the "vibe" of the ticket queue throughout the day. Agents can select a mood (emoji), optionally write a short note, and submit it. Logged entries are stored in a Google Sheet and visualized as a bar chart of today's mood trends.

## Features

- Select from 4 mood emojis: 😊 😠 😕 🎉
- Add optional notes like “lots of Rx delays today”
- Submit logs directly to a shared Google Sheet
- View a bar chart showing today’s mood distribution (Plotly + Matplotlib)

## Tech Stack

- Python (Google Colab / Jupyter)
- `gspread` + `oauth2client` (for Google Sheets API)
- `ipywidgets` (for interactive UI in notebook)
- `plotly` and `matplotlib` (for charts)
- Google Sheets (as database)

## How to Run 

1. Set up a Google Cloud project with the **Google Sheets API enabled**
2. Create a **service account** and download your `creds.json` file
3. Share your target Google Sheet with the service account’s email
4. Upload `creds.json` in Colab
5. Run all cells in order

## Files

- `moodtracker.ipynb` — interactive notebook with UI + plotting
- `README.md` — this file

## Additional Links
- 🧾 Google Sheet: [View Sheet]([https://docs.google.com/spreadsheets/d/YOUR_SHEET_ID_HERE](https://docs.google.com/spreadsheets/d/1DvJzFItN61QgzXS9OB_FUEltq6idruWNjoW0HP1ys8s/edit?usp=sharing))

