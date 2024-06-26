## Welcome to the DataWave Bodensee GitHub Page

We are a group of five students from the University of Konstanz and participated in the data4good Festival 2024 by the Hertie School. Our project aims to support the work of the Missing Migrants Project by the International Organization for Migration (IOM) by developing a tool that helps to improve the data collection. 


Our project uses a multi-stage pipeline to scrape and filter news articles to simplify the work of the IMO agents. The pipeline makes use of the zero-shot capabilities of Large Language Models to find relevant articles and extract important information.
A strength of the pipeline is the human-AI interaction, which allows the IMO agents to review the data and make necessary changes. This ensures high data quality while keeping the process efficient.

![image](https://github.com/DataWave-Bodensee/.github/assets/39091877/7aee2991-25fc-460c-890b-01a5eb74b5f3)


### Deployment
All components (containers and database) of this project are deployed in Microsoft Azure \
The demo is publicly available [https://missing-migrants.azurewebsites.net](https://missing-migrants.azurewebsites.net/) (untill our azure credit is empyt ¯\\_(ツ)_/¯).

### Repositories
Ther [scraper](https://github.com/DataWave-Bodensee/scraping) is responsible for news gathering and AI processing. \
The [backend](https://github.com/DataWave-Bodensee/backend) serves HTTP API endpoints to access the data. \
The [frontend](https://github.com/DataWave-Bodensee/frontend) gives a human agent access to the data. \


