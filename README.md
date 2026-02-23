# Personal-Public-Repository
Persona repository for different projects and developments
First Project - NBA Fantasy Basketball App waiver wire analyzer. Trying to identify optimal players to pick up based on schedule, current stats and player rankings.



fantasy-bball-pickups/
├── README.md
├── requirements.txt
├── .gitignore
├── data/
│   └── .gitkeep
├── src/
│   ├── __init__.py
│   ├── fetch_players.py       # pulls NBA stats via API
│   ├── score_players.py       # ranking logic
│   └── display.py             # CLI output (expandable to web)
└── main.py