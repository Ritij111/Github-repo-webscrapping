# Github-repo-webscrapping
Scraping top Repositories for topics from GitHub
Web Scraping:

Web scraping is the automated process of extracting information from websites, typically through software or scripts, to gather data for analysis or other purposes.
GitHub:

GitHub is a web platform for collaborative coding, offering version control tools to manage code changes and enable teamwork on software projects.
About Project and Project Outline:

In this project we are to scrape https://github.com/topics
We'll get a list of topics. For each topic, we'll get topic title, topic page URL and topic description
For each topic, we'll get the top 20 repositories in the topic from the topic page
For each repository, we'll grab the repo name, username, stars and repo URL
For each topic we'll create a CSV file in the following format:
Username, Repo_name, Stars, Repo_URL
mrdoob, three.js, 69700, https://github.com/mrdoob/three.js
libgdx, libgdx, 18300, https://github.com/libgdx/libgdx
Tools used

Python, requests, Beautiful Soup, pandas
