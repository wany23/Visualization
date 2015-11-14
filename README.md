#Titanic Data Analysis
*Wandrille Hubert*
*Note: index.html is the final version*

##Summary

I decided to examine the titanic data.  This consists of various demographic information about the passengers on the titanic and with the indication of whether they survived or not.  In my findings, it is found that females overall, regardless of ticket class, tend to have a higher survival rate than the males.  Furthermore, a higher success rate was seen with the younger the person's age was in the males.  In the females, this pattern of a higher success rate in younger females was much milder, and not as easily seen as with the males.  This follows in line with the "moto" of save the women and children first.

##Design

In examining this data, I used R.  Through this I was able to inspect the data, as well as formulate possible messages to display.  I decided that I would try to categorize by gender and age groups.  For my age groups, I chose to divide it into children from 0-18, young adult from 19-40, old adult from 41-65, and senior from 66+.  

For my design I started off with a general chart broken up by class and showing the survivor numbers between female and male.  This chart lacks information in that it is only showing the number of survivors, but does not show the number of people that died.  Thus, it is hard to tell how many people survived out of the total number of people in each class and gender.

Thus I slowly started to manipulate the data in order to portray what I wanted to display.  First of all, I broke apart females and males.  Then I changed the y axis to being a survived percentage instead of a number of people.  This gave a better representation of how many people actually survived over the total number of people.
Afterwards, I decided to categorize the data even further into age groups (Children 0-18, Young Adult 19-40, Old Adult 41-65, and Senior 66+).  From here I wanted to be able to keep the distinction between female and male, all the while being able to portray a message through this graph.  Thus I wanted to create a way to have it show data for females and males all at the click of a button.

I tried to do this with just one chart, but upon creating multiple legends, I appeared to run into issues of data not showing and the chart not how I want it to be.  After countless hours, I was able to find that by creating another chart just for the female and male selection, I was able to get what I wanted (by looking at the forums was I able to find a solution).  Thus I created an interactive legend through the creation of another chart, which would update the main chart with the selected variable (which sex).

I was able to incorporate the feedback I received and improve on my design.  Each time I got feedback and incorporated the changes, I could see my chart getting better and better.  The only issue I have left that I was not able to figure out was changing the color of the selected gender box.  I would like to change the color of the selected box in order to give the viewer a better idea of which gender’s statistics are currently showing.

Finally, I decided to clean up my index file and create a css and js file.  This helps break up the various parts of the website and makes it more clean in my opinion.
Note that I went through various iterations and this can be seen from the index_1, index_2, … Note that index.html is the final version.

##Feedback

I showed this person version 3 (summarized what they said to me):
This chart is great in separating the differences between genders.  Also it is very easy to see the differences between the different ticket classes.  However, this graph fails in picturing the number of people that survived over the total number of people on board.  The y axis should be a percentage instead of a number of people.  Furthermore, it would be great to extract more information out of the data.  Breaking it up only by gender does not seem to portray enough of a picture that could be portrayed from the data.

I showed this person version 5 (summarized what they said to me):
The chart itself was good.  However, the x-axis title as well as the y axis titles' both lacked proper titles.  Also, once the animation is done, you are not able to toggle between females and males.  The animation itself was a good feature, and really showed the difference between male and female survival rates.  The colors themselves between the bar charts were great, and really helped separate the different categories.  Also, the x axis show the decimal, but yet this is in relation to ticket classes, and thus appears weird.

I showed this person version 5 (summarized what they said to me):
I liked the animation in the graph, but it took a very long time for it to start up.  Also it took some time to realize that the animation was showing statistics for males and females.  The title is also a little misleading since you are also classifying along age groups.  Besides that, I really like the layout and the choice of categories.  Splitting up the statistics by gender was really portrayed well with the animation and noticing the change in survival rates between females and males.

##Resources

http://dimplejs.org/advanced_examples_viewer.html?id=advanced_interactive_legends
https://discussions.udacity.com/t/project-titanic-data-visualization/31754
https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.legend
http://stackoverflow.com/questions/12643591/how-to-limit-d3-svg-axis-to-integer-labels
