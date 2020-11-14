[![Work in Repl.it](https://classroom.github.com/assets/work-in-replit-14baed9a392b3a25080506f3b7b6d57f295ec2978f6f33ec97e36a161684cbe9.svg)](https://classroom.github.com/online_ide?assignment_repo_id=311731&assignment_repo_type=GroupAssignmentRepo)
# Group 100 - Anime-ted

- Your title can change over time.

## Milestones

Details for Milestone are available on Canvas (left sidebar, Course Project) or [here](https://firas.moosvi.com/courses/data301/project/milestone01.html).

## Describe your topic/interest in about 150-200 words

Japanese Animation, colloquially known as **Anime** has taken the world by storm, especially recently, and I have been invested in this field for quite some time. "**MyAnimeList**" is a database website that records almost every anime in existence, along with giving its users the opportunity to rate their favourite anime on a scale of 1 to 10. There is a lot to learn about this dataset, like *What genre of anime is popular amongst people that have seen very few anime vs. the genre that is popular among anime veterans?*, or even something like *Do people rate anime movies/OVAs higher over traditional episodic series?* As the market for anime continues to grow by the day, it might be useful to look back at what the viewers feel, allowing us to make informed choices as to what direction this industry could/should take in the future... 

## Describe your dataset in about 150-200 words

The **Anime Recommendations Database** dataset contains *metadata and information of around **12,000** different anime series/movies/OVAs etc, along with **76000** user ratings for these anime*. The anime metadata and the user ratings were collected through a public database site called [MyAnimeList](https://myanimelist.net/). The dataset is divided into two separate spreadsheets called "anime.csv" and "rating.csv", located in `data/raw`([here](data/raw)). 

The `anime.csv` file contains the following fields:
* A unique ID to identify each anime generated by myanimelist.net (**anime_id**)
* The full name of the anime (**name**) 
* A comma-separated list of each genre the anime falls under (**genre**)
* Whether the anime is a TV series, a movie, an OVA, etc (**type**) 
* The number of episodes the anime has (which is 1 for movies) (**episodes**)
* The average user rating out of 10 for the anime (**rating**), and
* The number of members that are in the anime's "group", i.e. the number of MyAnimeList users that are fans of the anime (**members**).

The `rating.csv` file contains the following fields:
* The unique user id generated by MyAnimeList (**user_id**)
* The unique anime ID of the show the user rated which corresponds to the field in `anime.csv` (**anime_id**), and
* The rating out of 10 that a particular user gave to the anime with the anime_id (which is -1 if the user has not rated it) (**rating**).

I will be using these two files for my analysis.

## Team Members

- Abhineeth: 3rd year CS major very interested in practical applications of Data Science

## References
[MyAnimeList](https://myanimelist.net/)
