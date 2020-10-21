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
6. Wikipedia Streaming Service Providers/Acadamy Award Best Picture Nominees

### Data Limitations
- <b> Lack of data on the geographic breakdown of streaming subscriptions </b>
- <b>Racial Categories</b> 
<br>The Census Bureau limits race to 5 categories: White, Black, Asian, Hawaiian Native/ Pacific Islander and Native American/ Alaskan Native, with Native American/ Alaskan Native defined as people originating from North, Central and South America. According to the Bureau, Hispanic and Latino is considered an ethnicity, not a race. For that reason, Hispanic and Latino is not included as a racial category. If given more time, we would look into representation for Hispanic and Latinos in Hollywood.  
<br>Actors were categorized by key words contained in their "ethnicity" string. In some cases, an actor had an ounce of African blood, which led to the actor being categorized as Black. Because this does not reflect the representation needed in Hollywood and significantly skewed the data for POC, we updated the database with more accurate information.  

### Methodology 
In our research for this project, we focused on what it could mean for Microsoft to start a film studio that values "Diversity and Inclusion." We gathered data on international films, potential competitiors, top-grossing actors, and films tagged with key words that could highlight marginalized stories, to analyze its financial and reputational rewards.

### Results 
<b>The Financial Aspect</b>
<br><i>Found in Part 1 - Target Market and Financial Opportunity.ipynb</i>

##### Where should Microsoft target its movie production efforts? 
<br>As an multinational company with wide gobal influence, Microsoft has the leverage to grow a successful movie content creation business line on a global scale. In terms of of revenue and growth however, its starting point may not necessarily be most productive if it were to focus its efforts domestically in the United States. 
The data in this section attempts to narrow down a target market for Microsoft as a starting point to launch their new movie studio. 
We look at box office data as a marker of market size, of the growth of the industry and audiences within a selection of 20 countries.
![alt text](https://github.com/christianmoya/Phase1_Project/blob/main/project_images/all_countries_growth.png)
<br>
Zooming in on the remaining countries, other that the United States and China:
<br>
![alt text](https://github.com/christianmoya/Phase1_Project/blob/main/project_images/global_box_minus_usa_china.png)

Our findings suggest that although the United States has the largest and most developed film industry, its growth rate since 2000 is amongst the lowest in the studied countries. Instead, countries like China, India and Brazil have shown impressive growth over the past 20 years, as seen in the chart below:
<br>

![alt text](https://github.com/christianmoya/Phase1_Project/blob/main/project_images/box_office_growth.png)
<br>
Furthermore, with subscription streaming becoming an increasingly important model to generate revenue in this industry, we take a preliminary look at the geographic spread of the present service providers in this regard, as they would be Microsoft's direct competitors in the distribution of its content. 
We find that the United States has the most competitors which is to Microsoft's disadvantage considering the low likelihood of acquiring licensing for non-Microsoft produced video content combined with the present lack of a deep selection of existing original content. 
<br>
![alt text](https://github.com/christianmoya/Phase1_Project/blob/main/project_images/competition_map.PNG)
<br>
These findings suggest that Microsoft has the opportunity to brand itself as an international film supporter, gathering significant market share of the international film industry while generating positive and growing revenue.
<br>

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
<br><br>In previous years, film studios recieved criticism regarding the lack of diversity of its cast. Movements like #OscarsSoWhite in 2015 and #whitewashedOUT in 2016 demanded for more representation in Hollywood. Consequently, we looked into the racial makeup of the Top Grossing Actors to find if the Box Office has responded to those demands. We asked, "How has the Top Grossing Actors changed since 2010?"

To answer this, we found data from the-numbers.com, which provided the 100 top grossing actors from 2010-2020, ranked by their <b>star score</b>, a score given to actors based on the number of top-grossing films they are featured in. At a quick glance, we could see an immediate shift from 2010 to 2020- with 2010's Top 3 being Robert Downey, Jr., Taylor Lautner, and Shia LaBeouf, and 2020's Top 3 being Samuel L. Jackson, Dwayne Johnson, and Danai Gurira. With that data, we looked at how star scores have changed for each racial category over time. The catplot below details out the star scores for actors of color in the last decade. By the turn of 2020, the average star score has gone up by 72% for Black actors, 36.7% for Native American/Alaskan Native actors, 21.5% for Asian actors, and from non-existent to 377.5 for Native Hawaiian/ Pacific Islander actors. 
<br>
![alt text](https://github.com/christianmoya/Phase1_Project/blob/main/project_images/starscore_POC.png?raw=true)

That's definitely reason to celebrate. Not only are average star scores going up for actors of color, we also find that the racial makeup of our Top 100 Grossing Actors to be much more diversified. In 2010, there were only 9 actors of color in the top 100. Come 2020, there are now 34 actors of color, with an <b>increase of 25 more actors of color</b>.
<br>
![alt text](https://github.com/christianmoya/Phase1_Project/blob/main/project_images/racial_count.png?raw=true) 

Still, film industries have a huge opportunity. Although there are more actors of color in the top-grossing films, actors of color also have a higher billing average. In performing arts, billing is a number that signifies your importance in a film. Actors with a lead role, would get a billing of 1, while supporting actors attain a higher billing. Our analysis shows that the billing average has gone up <i>significantly</i> for 3 racial groups: Black actors from 1.8 to 7.1, Asian actors from 1.9 to 10.6, and Native American/ Alaskan Native actors from 3.6 to 24. This means actors of color are casted for less important roles. Microsoft has the power to change that. 
<br>
![alt text](https://github.com/christianmoya/Phase1_Project/blob/main/project_images/average_billing.png?raw=true)



### Conclusions
<br> Microsoft should target international markets, where the industry growth rate is faster and comeptition is lower to capture the greatest revenue generating potential while creating a dominant brand name. Leveraging its global influence, Microsoft would capture rapidly growing audiences and revenues in these regions while branding itself as a supporter of international films. 

<br> Microsoft should focus on films from countries that garner cricial acclaim and participate heavily in awards campaigning in order to include their films in the greater history of film itself. 

<br> Microsoft can take the lead in creating films that not only feature people of color, but cast them in lead roles. Microsoft's values share the "transformative power of engaging many different perspectives," and showcasing the stories of people of color is one great way to do that.  

### Future Work 

Future analysis could include a deeper look into a successful distribution model and market for Microsoft's Movie studio, for a more targeted growth strategy for the company. As far as diversity, we could look into the diversity of the most popular TV shows as well. 
