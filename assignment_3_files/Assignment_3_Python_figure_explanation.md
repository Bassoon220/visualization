DSI Doctoral Certificate
Visualization Assignment 3
June 16, 2026, Robert Lu

Justification for the Python figure:

> What software did you use to create your data visualization?

I used a jupyter notebook (python).

> Who is your intended audience? 
    
My intended audience is myself. I made a plot of the frequency of delays for the 504 Streetcar line, which is the most common streetcar line that I use. I wanted to see if there's a pattern to when delays happen so that I can better plan my commutes.

> What information or message are you trying to convey with your visualization? 
    
I wanted to show the frequency of delays as a function of total trips to know when delays may be more or less likely to occur. However, given the data that was easily accessible on the City of Toronto website, I couldn't find total trip data, so I could only plot when reported delays occurred.

> What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    
I wanted the plot to be as simple as possible while being informative. Thus, it's just two histograms stacked on each other. One histogram is the frequency of delays for all weekdays, and the other hist is for delays only on Tuesdays, the day I use that line the most. The default bar style was too visually cluttered so I reduced the linewidth. I also chose bar colors which were complementary.

> How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    
First, I downloaded the data from the City of Toronto, so the plots should be reproducible if the same files are used. There's no random sampling involved. What can change is that the data can be updated but redownloading more recent versions and then adjusting the plots to use the newer data. The data plot reports of streetcar delays, which would be due to mostly human factors but also mechanical. If neither of those change when new data is downloaded, then I don't expect the figure ot change much.

> How did you ensure that your data visualization is accessible?  
    
I picked colours which were complementary and reduced visual clutter.

> Who are the individuals and communities who might be impacted by your visualization?  
    
I'm impacted ... from the figure, there doesn't appear to be any trend in the number of delays throughout the day. Given that service is increased during the rush hours, it's pretty impressive that the raw frequency of delays stays pretty constant. I don't think this data woudl be very useful to the public or anyone else because I think it really needs to be normalized by total number/frequency of trips. Also it wouldn't affect anyone not using the 504 King.

> How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    
I chose data which I thought would be easy to plot but also relatively useful. Geographic data is hard to plot, for example, the location of stops on a map. The time of delays would have been interesting to plot but I felt that just looking at frequency was good enough. The categorical data looked like it needed cleaning, and I didn't have time for that. There's much more that could have been done, like plotting data for other routes, but I didn't have enough time to think through how to work the data.

> What ‘underwater labour’ contributed to your final data visualization product?

First, someone/something has to be logging the delays. Then they need to compiled and then updated - the update schedule is monthly. The CKAN team had to develop a tool which easily allows the data to be stored and shared. The coding tools I used needed to be developed. I had to look up some documentation to make the plots. I also had to explore the data, in python and Excel, to decide which features to plot.
