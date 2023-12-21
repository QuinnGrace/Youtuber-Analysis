# YouTuber Analysis

## Expected Outcomes
- Identify trends in the top streamers and their audiences
- Propose a system for enhancing content recommendations to YouTube users based on streamers' categories and performance metrics

## Tools Used
- Jupyter Notebook (Python)
- Matplotlib
- Seaborn
- Pandas

## Output
This is only a snapshot of the analysis done, please see the notebook in the repository for more.

![linkedin5](https://github.com/QuinnGrace/Youtuber-Analysis/assets/73368635/fd764727-a9df-4e99-8ecd-dd9f48423c76)

![linkedin6](https://github.com/QuinnGrace/Youtuber-Analysis/assets/73368635/facd6420-b507-4045-a4b0-56792ade23af)

![linkedin7](https://github.com/QuinnGrace/Youtuber-Analysis/assets/73368635/4e7f1979-2228-42df-950d-4e7983286cf6)

![linkedin8](https://github.com/QuinnGrace/Youtuber-Analysis/assets/73368635/1b7b45c9-75f1-44d1-adfc-80d9d8444a11)

## Conclusions
- The most popular categories appear to be toys and movies about video games
- Rank was weakly inversely correlated with the number of visits and strongly inversely correlated with the number of subscribers.
- Categories were weakly inversely correlated with country, so YouTubers tend to have categories correlated with the country they are in.
- Visits were strongly correlated with likes, moderately correlated with comments and weakly correlated with subscribers.
- Likes were moderately correlated with comments and weakly correlated with subscribers.
- Streamers from African countries appear to have the lowest subscriber counts (specifically Egypt, Morocco, and Somalia). Streamers with the highest subscriber counts came from a variety of countries (Ecuador, India, and unknown).
- Music and dance is the most common category in most countries, with the notable exception of YouTubers from an unknown country being more likely to make animation videos. In Indonesia, Mexico, and Russia, Movies are the most popular category type.
- YouTube channels about video games, humor get about 10 times the visits that the average YouTube channel gets.
  
## Recommendations
Many recommender system suffer from a "cold start" problem where they do not have information once a user first joins about their preferences. To overcome this problem, YouTube could recommend videos from the categories and streamers that are performing the best at that point in time, adjusted for the location of the user and local preferences. YouTube has a very powerful algorithm but struggles in the beginning, this may help alleviate the issues in the beginning by catering to what is likely to resonate with the average user.
