# YouTube Channel Video-Data Downloader

This Python script allows you to fetch information about all the videos in a YouTube channel and store it in an Excel file.
## Requirements

Before running the script, make sure you have the following installed:

    Python 3.x
    pandas library (pip install pandas)
    google-api-python-client library (pip install google-api-python-client)

## Getting Started

    Obtain an API key from the Google Developers Console:
        Go to https://console.developers.google.com/
        Create a new project if you don't have one already.
        Enable the YouTube Data API v3 for the project.
        Create credentials for the API and get your API key.

    Replace the API-Key placeholder in the code with your actual API key.

## How to Use

    Run the script and provide the YouTube channel ID when prompted.

    Enter the desired name for the output Excel file (without the extension).

## Script Functionality

    The script fetches information about all the videos in the specified YouTube channel.
    It retrieves details like video title, URL, publication date, number of likes, views, and comments for each video.
    The data is stored in a DataFrame and exported to an Excel file for further analysis.

Note: The script fetches a maximum of 50 videos per request. If the channel has more than 50 videos, it automatically fetches the next page of results until all videos are retrieved.

Please ensure you use the script responsibly and adhere to YouTube's API usage policies.
