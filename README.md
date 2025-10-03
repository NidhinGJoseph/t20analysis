T20 World Cup 2024 Data Analysis

This project analyzes T20 World Cup 2024 ball-by-ball data to generate insightful batting and bowling statistics. Using Python (pandas, numpy) in Google Colab, the notebook extracts raw match data and processes it into meaningful team-level performance metrics.

Summary

Dataset: Ball-by-ball match data from T20 World Cup 2024 (FullT20wc2024.xlsx).
Objective: Transform raw cricket data into summarized batting and bowling statistics for each team.

Outputs:

Bats_stats.xlsx → Team-wise batting performance (Runs, Strike Rate, Average, Boundaries, High Scores).
Bowler_stats.xlsx → Team-wise bowling performance (Wickets, Economy, Strike Rate, Dot Balls, Best Bowling Innings).

⚙️ Features
Batting Stats
Matches played per team
Total runs scored
Boundaries (4s, 6s)
Dot balls faced
Wickets lost
Derived metrics:
Batting Average = Runs ÷ Outs
Strike Rate = (Runs ÷ Balls) × 100
Highest Team Score
Bowling Stats
Matches played per team
Runs conceded
Balls bowled & Extras
Boundaries conceded (4s, 6s)
Dot balls bowled
Wickets taken
Best Bowling Innings (BBI)

Derived metrics:

Bowling Average = Runs ÷ Wickets
Economy Rate = Runs ÷ (Balls ÷ 6)
Bowling Strike Rate = Balls ÷ Wickets

Installation

Clone the repo and install dependencies:

git clone https://github.com/your-username/T20-WC-Analysis.git
cd T20-WC-Analysis

# Install dependencies
pip install pandas numpy openpyxl

Usage

Upload the dataset FullT20wc2024.xlsx into /content/ in Colab.

Run the notebook:

# Run in Colab or Jupyter
!python T20_WC.ipynb


Output files will be generated:

Bats_stats.xlsx
Bowler_stats.xlsx


🤝 Contributing

Fork this repo

Create a new branch (git checkout -b feature-name)

Commit your changes (git commit -m "Added feature")

Push and open a Pull Request

📜 License

This project is open-source under the MIT License.
