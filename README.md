# video games
identifying popular video games for planning an advertising campaign for 2017

The dataset can be found here:<https://www.kaggle.com/akylson/gameplatforms2016>

We have data from an online store which sells video games all over the world. User and expert reviews, genres, platforms (e.g. Xbox or PlayStation), and historical data on game sales are available from open sources. WE will identify patterns that determine whether a game succeeds or not. This will allow us to spot potential big winners and plan advertising campaigns.We have data going back to 2016. We're planning a campaign for 2017.
The dataset contains the abbreviation ESRB. The Entertainment Software Rating Board evaluates a game's content and assigns an age rating such as Teen or Mature.

**Step 1. Open the data file and study the general information**

**Step 2. Prepare the data:**
- Check data types and deal with missing values
- Calculate the total sales (the sum of sales in all regions) for each game.

**Step 3. Analyze the data:**
- Look at how many games were released in different years. Is the data for every period significant?
- Look at how sales varied from platform to platform. Choose the platforms with the greatest total sales and build a distribution based on data for each year. Find platforms that used to be popular but now have zero sales. How long does it generally take for new platforms to appear and old ones to fade?
- Which platforms are leading in sales? Which ones are growing or shrinking? Select several potentially profitable platforms.
Are the differences in sales of all games broken down by platform significant? What about average sales on various platforms?
- Take a look at the general distribution of games by genre. What can we say about the most profitable genres? 

**Step 4. Create a user profile for each region:**
- For each region (NA, EU, JP), determine:
- The top five platforms. Describe variations in their market shares from region to region.
- The top five genres. Explain the difference.
- Do ESRB ratings affect sales in individual regions?

**Step 5. Test the following hypotheses:**
- Average user ratings of the Xbox One and PC platforms are the same.
- Average user ratings for the Action and Sports genres are different.

**Step 6. Write a general conclusion**

**Data description**
- Name
- Platform
- Year_of_Release
- Genre
- NA_sales (North American sales in USD million)
- EU_sales (sales in Europe in USD million)
- JP_sales (sales in Japan in USD million)
- Other_sales (sales in other countries in USD million)
- Critic_Score (maximum of 100)
- User_Score (maximum of 10)
- Rating (ESRB)
