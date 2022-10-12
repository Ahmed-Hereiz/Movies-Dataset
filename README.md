# Movies-Dataset

# Here I want to answer 4 questions which are : 

> - What is the most frequent genre in the dataset? <br><br>
> - What genres has highest votes? <br><br>
> - What movie got the highest popularity? <br><br>
> - Which year has the most number of movies? 

# First : I will begin exploring my data.
## After exploring data I noticed that : 
> - dataframe has 9827 rows and 9 columns. <br><br>
> - No NaN values nor duplicated values. <br><br>
> - Overview and Poster-Url wouldn't be so useful during analysis, so we'll drop them. <br><br>
> - There is many movies with Vote count = 0 and Vote average = 0, which is a very strange thing !!! <br><br>
> - Release_Date column should be date and I will make it focus only on year. Because I don't care about neither month nor day then I will change that date to int

# Second : I will begin cleaning my data.
### So I dropped useless rows then I checked why Vote count = 0 and Vote average = 0, and I found that the reason is because that this because this movies where not out yet and there is other movies that was underrated... So whatever the reason I don't realy care about these movies, So I dropped it. <br><br> Then I made years column as integer containing only the year as integer.

# Third : I will visualize data and try to get insights.
> - I visualized quantitative columns using violin plot to show where data is most <br><br>
> - I showed every movie Genre and number of movies with these Genre on a barplot where I found that Most frequent Genre is Drama then Comedy then Action <br><br>
> - I grouped data according it's popularity into 3 groups (popular - average - not popular) <br><br>
> - Using this grouped data to know which movie genre is most popular (using grouped data) So Single Genre with the highest votes is Drama then Comedy then Action <br><br>
> - I wanted to show top 10 movies popular and top 10 movies with high vote count So I scattered plot these movies <br><br>
> - I wanted to show top 3 movies popular and top 3 movies with high vote count so I but there posters in the notebook and I found that Highest popularity movie is Spider-Man: No Way Home then The Batman then No Exit and Movies with highest votes is Inception then Interstellar then The Dark Knight <br><br>
> - I wanted to show year with the most films made so I lined plot dates and I found that most movies was made in 2021

# Fourth : Summary.
> - Most frequent Genre is Drama then Comedy then Action. <br><br>
> - Single Genre with the highest votes is Drama then Comedy then Action. <br><br>
> - The Genre with the highest votes is (Action, Science Fiction, Adventure) which belongs to Inception. <br><br>
> - Highest popularity movie is Spider-Man: No Way Home then The Batman then No Exit. <br><br>
> - Movies with highest votes is Inception then Interstellar then The Dark Knight. <br><br>
> - Year that has the most number of movies is 2021.
