# Y.Music: A Comparative Study of Music Preferences in Springfield and Shelbyville
## by _Mila Lestari_

[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)

This is my first project and I'm excited to work on it. I'm eager to learn and grow both personally and professionally. I am committed to making this project a success.

## Features
> With each analysis,
> we establish several hypotheses that require thorough testing.
> Sometimes, our testing confirms these hypotheses.
> However, there are occasions when we must refute them.
> To make sound business decisions, it's crucial to assess the validity of our assumptions.

## Introduction <a id='intro'></a>
Whenever we conduct an analysis, we need to formulate several hypotheses that we will test further. Sometimes, the tests lead us to accept these hypotheses, while other times, we need to reject them. To make informed business decisions, we must understand whether the assumptions we make are correct or not.

In this project, we will compare the music preferences of listeners in the cities of Springfield and Shelbyville. we will review real data from Y.Music to test the hypotheses below and compare user behavior in both cities.

### Goal:
Test three hypotheses:
1. User activity varies depending on the day and the city.
2. On Monday mornings, residents of Springfield and Shelbyville listen to different genres. This is also true for Friday evenings.
3. Listeners in Springfield and Shelbyville have different preferences. In Springfield, users prefer pop music, while in Shelbyville, rap music is more popular.

### Steps
Data related to user behavior is stored in the file [**music_project_en.csv**](https://raw.githubusercontent.com/milawidyalestari/data-analyst-ml-project/project1-y.music-behavior/music_project_en.csv). There is no information about the quality of this data, so we need to examine it first before testing the hypotheses.
This project consists of three stages:
1. Data Overview
2. Data Preprocessing
3. Hypothesis Testing

### Column Description:
- 'userID' — User ID
- 'Track' — Song title
- 'artist' — Artist name
- 'genre'
- 'City' — User's city of origin
- 'time' — Time the song was played
- 'Day' — Day of the week
