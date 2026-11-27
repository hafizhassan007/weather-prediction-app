# Storm Prediction Agent

Live weather, storm/rain prediction and news-ready PDF reports, built with
LangChain Deep Agents and Streamlit.

## Run it
```bash
uv sync
cp .env.example .env      # Windows: copy .env.example .env  (then add your keys)
uv run streamlit run app.py
```

## Files
- weather_api.py - gets live data and calculates storm risk
- pdf_report.py  - builds the PDF
- main.py        - the deep agent and its tools (run alone: uv run main.py)
- app.py         - the Streamlit website