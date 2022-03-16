# NETFLIX-MOVIES-AND-TV-SHOWS-CLUSTERING
![image](https://user-images.githubusercontent.com/85746056/156109575-107339ed-c1ed-4b3f-adc0-9c11d4f4ba7d.png)

## 1) Problem Statement
This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.

In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

## 2) In this project, you are required to do
1) Exploratory Data Analysis

2) Understanding what type content is available in different countries

3) Is Netflix has increasingly focusing on TV rather than movies in recent years.

4) Clustering similar content by matching text-based features

## 3) Attribute Information
* show_id : Unique ID for every Movie / Tv Show
* type : Identifier - A Movie or TV Show
* title : Title of the Movie / Tv Show
* director : Director of the Movie
* cast : Actors involved in the movie / show
* country : Country where the movie / show was produced
* date_added : Date it was added on Netflix
* release_year : Actual Releaseyear of the movie / show
* rating : TV Rating of the movie / show
* duration : Total Duration - in minutes or number of seasons
* listed_in : Genere
* description: The Summary description
![image](https://user-images.githubusercontent.com/85746056/156109719-f4f1693f-0491-43a2-b273-9cbcf4947630.png)

## 4. Data Visualization
### 1) Analyze the type of content available on Netflix
![image](https://user-images.githubusercontent.com/85746056/156109750-dd5ce093-2ab0-4245-b69e-6fc10204ad85.png)
* It is evident that there are more movies on Netflix than TV shows.

* Netflix has 5377 movies, which is more than double the quantity of TV shows.

### 2) Countplot for movie and Tv show ratings
![image](https://user-images.githubusercontent.com/85746056/156109841-50ae2de6-fc9b-40e9-90d0-e9f2fea3d729.png)
* The 'TV-MA' rating is used in the majority of the film. The TV Parental Guidelines provide a "TV-MA" classification to a television programme that is intended solely for mature audiences.

* The second largest is 'TV-14,' which stands for content that may be inappropriate for minors under the age of 14.

* The third most common is the extremely popular 'R' rating. The Motion Picture Association of America defines an R-rated film as one that contains material that may be inappropriate for children under the age of 17; the MPAA states that "Under 17 requires accompanying parent or adult guardian."
### 3) Growth in content over the years
![image](https://user-images.githubusercontent.com/85746056/156109931-cdd0e375-dc09-4f25-bcef-c7d4bc7cba20.png)

![image](https://user-images.githubusercontent.com/85746056/156109952-3fa91b60-b7bd-451c-9e30-54b4c6e11a89.png)

* The number of movies on Netflix is growing significantly faster than the number of TV shows.

* In both 2018 and 2019, approximately 1200 new movies were added.

* We saw a huge increase in the number of movies and television episodes after 2014.

* Because of covid-19, there is a significant drop in the number of movies and television episodes produced after 2019.

* It appears that Netflix has focused more attention on increasing Movie content that TV Shows. Movies have increased much more dramatically than TV shows.
### 4) Genres Analysis
![image](https://user-images.githubusercontent.com/85746056/156110079-39b97791-91d4-4e53-9163-6ed240265961.png)
* It is interesting that International Movies tend to be Dramas.

* Another observation is that International Movies are rarely in the Children's genres.
### 5) Netflix Content for different age groups in top 10 countries
![image](https://user-images.githubusercontent.com/85746056/156110146-f8a036bc-7b77-4da4-9afb-49529aa900c0.png)
* It is also interesting to see parallels between culturally comparable nations - the US and UK are closely aligned with their Netflix target ages, but radically different from, example, India or Japan!

* Also, Mexico and Spain have similar content on Netflix for different age group

