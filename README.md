# YouReddit Synergy Scraper: Multi-Platform Taste Profiler

YouReddit Synergy Scraper is a powerful web scraper and data processing tool that creates comprehensive user profiles based on their activity on YouTube and Reddit. These profiles can be used to build a powerful movie recommendation system that leverages user preferences across multiple platforms.

## Features

- Scrape user's liked videos and subscribed channels using YouTube Data API
- Extract metadata from YouTube videos and channels
- Scrape user's upvoted and downvoted posts and subscribed subreddits using Python Reddit API Wrapper (PRAW)
- Extract metadata from Reddit posts and subreddits
- Merge scraped YouTube and Reddit data based on user ID
- Create user profiles with metadata from both platforms
- Perform feature extraction and preprocessing to create a suitable dataset for recommendation systems
- Analyze merged user data to identify common interests and preferences
- Generate insights and visualize trends in user behavior across YouTube and Reddit
- Apply machine learning algorithms like clustering or topic modeling to group users with similar interests

## Installation

1. Clone the repository:

git clone https://github.com/ssaillant/YouReddit_Synergy_Scraper.git


2. Change to the project directory:

cd YouReddit_Synergy_Scraper


3. Install the required dependencies:

pip install -r requirements.txt

## Usage

1. Set up your API credentials for YouTube Data API and PRAW in the `config.py` file.

2. Run the YouTube scraper to collect user's liked videos and subscribed channels:

python youtube_scraper/yt_scraper.py

3. Run the Reddit scraper to collect user's upvoted and downvoted posts and subscribed subreddits:

python reddit_scraper/reddit_scraper.py

4. Merge the scraped data and create user profiles:

python data_processing/data_merger.py


5. Perform feature extraction, preprocessing, and analysis:

python analysis/data_analysis.py


6. Apply machine learning algorithms to group users with similar interests:

python machine_learning/clustering.py


## License

This project is licensed under the [MIT License](LICENSE).

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) for more information.

This README.md file provides an overview of the project, its purpose, features, installation instructions, and usage steps. It also includes information about the project's license and how to contribute to the project.
