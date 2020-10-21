# Film Analysis for Microsoft Film Studio 
Contributing Members: Anastasia Ulianova, Christian Moya, & Dylan Garsee

<img src='https://1.bp.blogspot.com/-LCNdmydj22w/XWBIIYwtbxI/AAAAAAAA09M/IvNxqGxSMKw5vC2YV2zg6tpAM-oB0TNWwCLcBGAs/s1600/00000000mm.png'>

### Project Overview
Given the plethora of film studios and streaming services, our team analysed recent trends to discover ways for Microsoft to stand out amongst its competitors when first entering the film industry. We used Microsoft's values to guide our investigation, honing in on the company's focus on Diversity and Inclusion and its "transformative power of engaging many different perspectives". We analyzed the awards and financial successes of international films, the diversity of the top-grossing actors worldwide over the last decade, and the return of investment for marginalized stories.  

### Data 
1. The Numbers - detailed database where film and numbers meet 
2. Ethnicelebs - find out the nationality, background, ancestry or race of famous celebrities
3. They Shoot Pictures, Don't They? - growing film resource dedicated to the art of motion picture filmmaking 
4. IMDb - the world's most popular and authoriative source for movie, TV and celebrity content
5. Box Office Mojo - website that tracks box office revenue 

### Data Limitations
- <b>Racial Categories</b> 
<br>The Census Bureau limits race to 5 categories: White, Black, Asian, Hawaiian Native/ Pacific Islander and Native American/ Alaskan Native, with Native American/ Alaskan Native defined as people originating from North, Central and South America. According to the Bureau, Hispanic and Latino is considered an ethnicity, not a race. For that reason, Hispanic and Latino is not included as a racial category. If given more time, we would look into representation for Hispanic and Latinos in Hollywood.  
<br>Actors were categorized by key words contained in their "ethnicity" string. In some cases, an actor had an ounce of African blood, which led to the actor being categorized as Black. Because this does not reflect the representation needed in Hollywood and significantly skewed the data for POC, we updated the database with more accurate information.  

### Methodology 
In our research for this project, we focused on what it could mean for Microsoft to start a film studio that values "Diversity and Inclusion." We gathered data on international films, top-grossing actors, and films tagged with key words that could highlight marginalized stories, to analyze its financial and reputational rewards.

### Results 
<b>Box Office for International Films</b> ... 

<b>Awards for International Films</b> 
<br><i>Found in critical_acclaim_pt2.ipynb</i>
<br><br>At the end of the day movies are art, and great art stands the test of time. Two metrics to determine the cultural legacy of films are film critics and the Academy Awards. Film critics are independent voices knowledgeable on the art of film, while the voting body of the Academy Awards are made up of people who work in the film industry of the United States. The data presented from the film critics is a compiled list of nearly 12,000 lists of the greatest films of all time. While the USA had the most films from an individual country on the list, combined there were a greater number of films from non-USA countries. The Top 4 countries whose films appear on the list are France, The UK, Japan, and Italy, which are also 3 of the 4 largest international markets as per my colleague Anastasia's data. 
![alt text](https://github.com/christianmoya/Phase1_Project/blob/main/project_images/1000_greatest_films.png?raw=true)
![alt text](https://github.com/christianmoya/Phase1_Project/blob/main/project_images/top_4_countries.png?raw=true)


While critical acclaim is great, recognition from the film industry itself is the highest honor a film can receive. The Academy Awards recognizes the year in film and is voted on by the American film industry. While there is a designated Best International Film category, more non-USA films have been showing up in the main category Best Picture. In fact of the 11 international films nominated for Best Picture over the 91 years, 7 of those nominees have been in the past 20 years, with Parasite, a South Korean film, actually winning the 2020 award. 
![alt text](https://github.com/christianmoya/Phase1_Project/blob/main/project_images/international_best_picture.png?raw=true)
<br>
  

<b>Diversity in Top-Grossing Films</b>
<br><i>Found in TopGrossingFilms_Diversity.ipynb</i>
<br><br>In previous years, film studios recieved criticism regarding the lack of diversity of its cast. Movements like #OscarsSoWhite in 2015 and #whitewashedOUT in 2016 demanded for more representation in Hollywood. This notebook seeks to find whether the Box Office has responded to those demands by analyzing the 100 top grossing actors for 2010-2020. Do audience members demand to watch more films featuring people of color? If so, what roles are they casted for- do they play the lead role or the supportive best friend with just 20 minutes of screen time? 

To answer this, we found data from the-numbers.com, which provided the 100 top grossing actors for each year, along with their star score and billing average. A star score is given to actors based on the number of top-grossing films they are featured in, while the average billing signifies their ranking of importance in a film. For each actor on the Top 100 list, we found their ethnicity by scraping data through ethnicelebs.com, then categorized their ethnicity into racial categories defined by the Census Bureau. With that data, we looked at how star scores have changed for each racial category over time. We found that star scores have gone up by 98, 63.5, and 377.5 points for Black, Native American/Alaskan Native and Native Hawaiian/ Pacific Islander actors consecutively, meaning more top grossing films feature people of color! 
<br>
![alt text](https://github.com/christianmoya/Phase1_Project/blob/main/starscore_average.png?raw=true)


We also find that although there are more actors of color in the Top Grossing actors list, actors of color carry a higher billing average, which means they play less important roles in those films. In 2010, there were only 9 actors of color in the top 100, then in 2020, that number increased to 34 actors of color. However, average billing has gone down significantly, especially for Native American/Aslaskan Native actors. Native American/Alaskan Native actors had an average billing of 3.6 in 2010, but 10 years later, went by 21.4 to an average billing of 24. 
<br>
![alt text](https://github.com/christianmoya/Phase1_Project/blob/main/racial_count.png?raw=true) 
![alt text](https://github.com/christianmoya/Phase1_Project/blob/main/top_4_countries.png?raw=true)



### Recommendation 
<br> Microsoft should focus on films from countries that garner cricial acclaim and participate heavily in awards campaigning in order to include their films in the greater history of film itself. 

<br> Microsoft can take the lead in creating films that not only feature people of color, but cast them in lead roles. Microsoft's values share the "transformative power of engaging many different perspectives," and showcasing the stories of people of color is one great way to do that. 

### Conclusion 

### Future Work 
