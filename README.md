# Wordle-Tweet-Analysis_Python
A comprehensive data analysis project exploring Wordle game results shared on Twitter. This project processes and analyzes over 1.1 million Wordle-related tweets to extract insights about player performance, game patterns, and social sharing behaviors.

📊 Project Overview
This project analyzes a dataset of 1,178,454 Wordle-related tweets to understand:

Daily tweet volume patterns

Player performance metrics (number of attempts to solve puzzles)

Game difficulty trends over time

The structure and meaning of Wordle tweet formats

📁 Dataset
The dataset (tweets.csv) contains 5 columns:

wordle_id - Integer identifier for each Wordle puzzle

tweet_id - Integer identifier for each tweet

tweet_date - DateTime of tweet (UTC)

tweet_username - Twitter username

tweet_text - Full text content of the tweet

🔧 Technical Implementation
Data Processing
Parsed tweet text to extract puzzle number and attempt count

Converted tweet dates to proper datetime format

Cleaned and structured emoji data for analysis

Analysis Features
Daily tweet volume tracking

Performance distribution analysis (how many attempts players typically need)

Time series analysis of game difficulty

📈 Key Insights
Most common number of attempts needed to solve puzzles

Daily engagement patterns with Wordle tweets

Changes in player performance over time
📋 Dependencies
Python 3.7+

pandas

numpy

matplotlib

Jupyter Notebook

🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgments
Dataset source: [https://www.kaggle.com/]

Wordle game by Josh Wardle

Twitter API for providing the tweet data

📧 Contact
For questions about this analysis, please open an issue in this repository.
Saraomran433@gmail.com
