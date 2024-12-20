# Web_Scraping_Analysis

In this project I performed an analysis on Mars News and Mars Weather data by scraping a website. I used Splinter to control the Chrome browser with automated browsing and then used Beautiful Soup to parse the information from the html. Next, I used Pandas to prepare and place the scraped data into a Dataframe, and used Matplotlib to plot the data into Visualizations that the user can see and understand.

The first plot shown here shows us the average minimum temperature by month:

<img width="823" alt="Screenshot 2024-12-20 at 4 54 09 PM" src="https://github.com/user-attachments/assets/ce127110-30b0-48d5-81df-7c7ef6b637bf" />

From the website (https://static.bc-edx.com/data/web/mars_facts/temperature.html) I was able to pull data from months Jan-Dec showing the minimum/coldest temperatures on Mars. After plotting and sorting the Months of the Year with the Minimum Temperatures found on Mars, we can clearly see that on average the coldest months of the year are March and April, and the hottest months of the year on average are August and September. We are not provided enough imformation to be able to figure out why these months are colder than others. If we did a deeper analysis we might be able to compare these temperatures to other planets to be able to give us more context.



The second plot show below presents the average pressure by month after its been sorted to show the lowest and highest average pressure months on Mars:

<img width="823" alt="Screenshot 2024-12-20 at 4 54 22 PM" src="https://github.com/user-attachments/assets/05be4c75-a638-4ff4-bf61-bf8f8faaf6bd" />

From the website (https://static.bc-edx.com/data/web/mars_facts/temperature.html) I pulled the data about Pressure on Mars. I calculated average pressure by month from Jan-Dec. I then plotted this data and sorted it to find the months with the lowest and highest pressure on Mars. The month with the lowest pressure appears to be June, and the month with the highest pressure appears to be September. Again, without more information about the context of this data I was unable to perform a deeper analysis of the significance of why pressure is higher or lower during these months.



This last and final plot shows how many terrestrial (earth) days there are in a Martian year:

<img width="823" alt="Screenshot 2024-12-20 at 4 54 31 PM" src="https://github.com/user-attachments/assets/8a63b749-31ec-48bd-88a3-9e94eb517136" />

From the analysis on minimum temperature from Jan-Dec across the entire data set in our data frame we can see that there are over 1750 and maybe a little under 2000 Earth days in a Martian year. 



