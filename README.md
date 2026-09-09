# NBA Season Simulator

An interactive Python-based NBA season and playoff simulator built using Pandas and IPython. This tool allows users to simulate full 82-game regular season schedules, adjust game strategies dynamically, review team game histories, and run best-of-7 playoff brackets all the way to the NBA Finals.

---

## Features

* **Custom Game Engine:** Simulates realistic game outcomes and overtime scenarios using offense, defense, and home-court advantage metrics.
* **Full Schedule Generator:** Constructs realistic 82-game regular-season schedules based on division and conference alignments.
* **Interactive Coaching & Strategy:** Manage your favorite team and alter strategy dynamically (e.g., Aggressive Offense, Lockdown Defense, or Balanced) for each game.
* **Playoff & Finals Engine:** Automatically seeds top teams from each conference into a best-of-7 series bracket to crown an NBA champion.
* **Game History & Analytics:** Filter and inspect specific team performances and season standings.

---

## Quick Start

### 1. Requirements
Ensure you have Python installed along with the required libraries:

```bash
pip install pandas ipython

```

### 2. Running the Simulator

Open `nba_simulator.ipynb` in **Google Colab** or **Jupyter Notebooks**, then run all cells:

```python
# Select your team and start the interactive season
user_choice = input("Enter the team you want to control: ")
season_results_df = run_interactive_season(teams, user_choice)

```

---

## How It Works

1. **Regular Season:** Choose to play each matchup step-by-step or fast-forward to the end of the season.
2. **Strategy Adjustments:**
* **Focus Offense:** Boosts offensive output (+5) while sacrificing defensive stability (-2).
* **Focus Defense:** Boosts defensive rating (+5) at the cost of offensive rhythm (-2).


3. **Playoffs:** Evaluates final standings to compute seedings (1 through 8 per conference) and runs complete playoff series.

---

## Project Structure

```text
nba-simulator/
├── nba_simulator.ipynb   # Main notebook containing simulator classes & logic
└── README.md             # Project documentation

```

```

---

### How to apply it:

1. Select **all text** inside your `README.md` tab in [Codespaces](https://stunning-space-waddle-97rxgw65jpvjc4j6.github.dev/) (`Ctrl + A` or `Cmd + A`) and delete it.
2. Paste the code block above into the file.
3. Save the file (`Ctrl + S` or `Cmd + S`).
4. In the Terminal panel below, run:
   ```bash
   git add README.md
   git commit -m "Complete README documentation"
   git push origin main

```