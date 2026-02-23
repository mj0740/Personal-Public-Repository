# Personal-Public-Repository
Persona repository for different projects and developments
 updated 10/8/2025


updated 2/22/2026

-- Fnatasy basketball pickup analyzer. Main data point to gather is NBA team schedules and games played for players that are currently available to pick up in my fantasy basketball leage.


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