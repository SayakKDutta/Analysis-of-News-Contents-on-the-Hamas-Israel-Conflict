# Analysis of News Contents on the Hamas-Israel Conflict

## Overview
This repository contains the analysis of news contents related to the armed conflict between Hamas and Israel, as reported by five different news agencies: Business Insider, TIME, Telegraph, Statesman, and BBC. The analysis focuses on one month of data to observe changes in keywords used in news articles over time, utilizing natural language processing (NLP) techniques.

## Data Collection
The news articles were pulled from the respective websites of the selected news agencies for the duration of one month. Only articles directly related to the Hamas-Israel conflict were included in the analysis. This was done manually by checking out how many pages will contain the data for one month and iterating over those pages for the websites. The data collected for month 17th Dec to 17th Jan (approx). 

Future Work: This data can be pulled by API for the timeframe.

### NOTE: To run the code one needs to copy the websites of the respective news (found in the notebook output) and include them in the respective dictionary found in the code and then on as it is. Or, needs to change the page number of the respective news websites by visiting the websites and manually checking the dates or can modify the code to pull data by their dates from the websites. Another alternative is using [NEWS_API](https://newsapi.ai/?gad_source=1&gclid=Cj0KCQjwltKxBhDMARIsAG8KnqVeZGr-oShFfKC19E6pgA_9U1Q2KgvkUzdJjBLK7UYpqdeQpleFY40aAs6fEALw_wcB) to collect data. 

## NLP Analysis
### Keyword Extraction
- Keywords were extracted from the news articles using NLP techniques.
- Dominant topics across news agencies were identified.
- Variation in coverage and common themes were analyzed.

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

 ## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.

## Acknowledgments
The dataset used in this analysis is collected from the websites of the respective news agencies and is publicly available.

## Contact
For any questions or feedback, please contact [sayak.kr.dutta1@gmail.com].
