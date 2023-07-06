# mystery_store
Predicting/Concluding a mystery store's production based on its top clientele 

# Data Tells The Story: A Mystery Store and Their Best Customers Summary #

## Introduction ##

Generally, when working with your data, you gain insights about your customers through the sale/distribution of your goods. With this dataset, the goal of our analysis was entirely flipped on its head. Instead of gaining insights on our customers through the business, this data would have us look for an insight into our business through the customers. No store names, inventory, or employees were listed in the original dataset. Instead, information expressing ages, family, and professional experience of our customers were provided to build a picture of its base clientele. And so, an opportunity was provided. How could one reverse engineer this dataset, and create a business profile for a mystery store?

### Data Breakdown ###
I needed to create a general overview for the average customer that may come into our store. My first thought was to find our split on gender, separating our data into two distinct A/B groups. Not only in sheer volume of sales, but individually spending more per person on average, women accounted for nearly 70% of all sales, indicating our major target market. Narrowing down our search, I could dive into the target market’s data.
Our data frame contained a column discerning the spending score of each customer during their visit. From 1-100, it ranked each customer on their spending habits as patrons. Their ranks made the perfect thresholds to identify the highest contributing customer types and separate each group by their respective rankings. Drilling in on the top contributors would provide ample markers to point us in the direction of the mystery store.
  
### Data Exploration ###
Pandas_profiling library was used to provide its ProfileReport module to display a full file for each group to create a skeletal framework for our average customer and their characteristics. By the Pareto Principle (80/20), we could assume that the top 20% of our customers represented 80% of our total sales. Identifying the groups as I had previously meant that we only had to look into the top percentile group of our customers to accurately assess our customer pool.
  
### Data Visualization ###
Via the profile report, I could now take our defining traits of the top customer base and visualize our theoretical customer in Tableau Dashboard. Taking our defined A/B groups, I saved the top percentile as a new dataframe csv file and exported the modified data into Tableau. The top 20% of our customer base carried a majority of trends reflecting in our total customer base. The dashboard was visualized such that we could reflect the division of total sales between male and female patrons. Discerning their average age and family size, both groups had very little deviation between their basic defining traits. Each group averaged in their late 40’s, with a family of 3-4, and major work experience.

### Customer & Store Profile ###
Since we knew most of our customers were women, the next step would be to look at the major profession counts from our customers. Artistry, Healthcare, and Entertainment topped the charts alluding that our store may be specialized in these areas. Homemakers interestingly, although having the lowest count, had the most work experience. With all the data we had uncovered, this would be the best chance to conclude our mystery business.
A female centric store, it mainly provided for artists & healthcare workers. Clearly, those who took care of households also knew that the store provided quality products. A large selection of professional supplies and ease of access is important with them. If it were a chain business, I would hypothesize the store being a large business like Michales or Hobby Lobby. Since we don’t know how many stores we are looking at, if it were a single business owner, I might conclude it being a boutique art store with specific, higher end supplies. The population of our clientele would suggest returning customers with specific artistic needs, and the business excels in providing them. The age range and work experience suggest that customers would be more inclined to shop for quality over price range.
  
 ### Future Actions ###
On a final note, I would like to touch on what our store’s next options would be to do with the conclusions derived from its customer's data. The store is already based in Creativity and art, so a switch in the target market would not be recommended. Instead, noting the imbalance of men and women in the store, I see two ways to approach future business. Notably, our male population is much lower, so initiatives to engage men or appeal to the demographic would bring in new untapped customers. Alternatively, the store could benefit by honing in on their current base, and learn more about their female clients to bring a more specialized or streamlined experience in sales. Essentially, it would be up to the business whether they would like to expand into new target markets (male), or expand the sales in their current market.
  
## Conclusions ## 
With enough data, the picture continues to become clear. With the limited resources I had, there was more than enough evidence to identify the business and suggest improvements to its model. With more information we could track purchase history and habits, or even personalize the inventory to our top clients’ tastes. Understanding your market at this angle opens up a plethora of new doors, not only increasing market sales, but tailoring an improved experience for the customers. 


### Tableau account

https://public.tableau.com/app/profile/anthony.shortt

### LinkedIn

www.linkedin.com/in/anthonyshortt
