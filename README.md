# romancerecs: Recommendation engine for romance books

## Plan:
1. Use GoodReads public data from [UCSD Book Graph](https://sites.google.com/eng.ucsd.edu/ucsdbookgraph/home?pli=1) and some sample code from [their github repo](https://github.com/MengtingWan/goodreads). 
2. Their data is a bit old so also scrape some recent data from [GoodReads](https://www.goodreads.com/)
3. Scrape [StoryGraph](https://app.thestorygraph.com/) for romance genre. They don't seem to have their own dataset or API.
4. Scrape Instagram for my favorite booksta influencers.
5. Scrape youtube for my favorite booktube influencers.
6. Join all possible data.
7. Use LightFM to build a recsys.
8. Features: genre (goodreads + storygraph), trad/indie (?), moods (storygraph), pacing (storygraph), steam level (youtube/insta/reviews/), tropes (reviews/insta/youtube), length (goodreads + storygraph), recommended by (reviews/insta/youtube).
9. **Join with [IMDB dataset](https://www.imdb.com/interfaces/) to find movies based on books.
10. Recommend: books, **movies, influencers based on my taste.
