# BikeshareProject
Using bike share data from three cities (New York, Chicago and San Francisco) I looked for interesting insights into the riders and network. After coming up with some interesting insights, I decided to focus on a part of the dataset that I found intriguing -- the late night/early morning users. My data analysis showed that there was a cohort of customers that utilized the bikes regularly at these times. 

I wanted to understand what the users might be doing pre and post bike usage. Since most offices are closed between midnight and 6am I decided to focus on leisure activities since bars, restaurants and nightclubs are often open during those hours. Since this information isn't available in the database I decided to add to the dataset using Google's Places API. I've pulled the name, price_level and user rating data regarding bars, restaurants and nightclubs within 270ft of bike hubs (the average length of a block in NYC). These data points will let me calculate which leisure option would be the best based on trip time.

To get an even more granular picture, I pulled web data for menu pricing for each restaurant and created a dataframe with prices. Adding price information to the calculation which should make my prediction of which leisure option to choose even better. From the businesses perspective, this could give them a probability that any given customer will choose their establishment. This information could be the business case for offering discounts or specials for bikeshare users during this midnight to 6am window.  





