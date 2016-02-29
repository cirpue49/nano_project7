Summary
    I used Baseball data and investigated the differences among the performances of the baseball players. Mainly I found two things. First of all, there is a positive correlation between the number of homerun and hitting average, which is explained by the location of plot. Second, those who have relatively big body hit more homerun than small body baseball player, which is explained by the color and size of plot.

Design
    At first, I made scatter plot like, x axis is avg(average), y axis is HR(the number of homerun) and colored plot with habdedness since it is effective to show many plots' relationship. However, this graph only showed nothing except for positive correlation between avg and HR. Furthermore, too many plots deprived the graph from telling other messages. I decided to use bubble graph which represents the number of homerun. I got feedback that it is wierd to use two ways of measurements to represent the number of homerun, which are y axis and the size of bubble. However, it helps us to focus on some plots, which are big sized plots. Also I bring this idea from the Facebook's IPO graph. 

    In addition, I scaled weight and height from 0 to 2 by using min and max scaling function in python. I definded scaling 0 to 1 as small body and 1 to 2 as big body. Based on this scaling and definition, I coloured bubble graph with red and blue. It is obvious that red bubble is more dominant than blue bubble. 

    Also, I did not scale down X axis from 2.0 to 3.5 since this graph have to show positive correlation between hitting average and the number of homerun. 

    From my data visualization, I want to tell two points in baseball data. First, there is a positive correlation between hitting average and the number of homerun. The second point is that bigger sized players more likely to hit homerun. 

Feedback
    I always asked my friends three questions. First, What do you think about this graph?. I wanted to know first impression of my graph. Second, My messages are properly conveyed or not. My messages are about correlation betweeen number of homerun and correlation between body size and player performance. Third, in order to make better data visualization which convey my messages, what can I improve in my graph. 

    I got feedback from three person. First, my graph fails to tell any messages since there are too many plots. I implemented bubble chart to draw readers attention to some plots.
    Second, X axis should be narrow down since plots are concentrated on more than 0.20 in X axis. I did not change my x axis since if I did, my first message would not properly conveyed. 
    Third is that it is weird to use two measurements to represent the number of homerun. It might be wired, but I decided to use two measurements for homerun to convey my messages. In addition, I encourage peole to understand what the circle side stands for by adding circular legend.

Resources
    Scatter Plot Example "https://bl.ocks.org/weiglemc/6185069"
    Y Axis Label "http://bl.ocks.org/phoebebright/3061203"
    Tooltip "https://bl.ocks.org/d3noob/a22c42db65eb00d4e369"
    Facebook IPO "http://www.nytimes.com/interactive/2012/05/17/business/dealbook/how-the-Facebook-offering-compares.html?_r=0"


    <!-- 1, about dot, color, size and opache. -->
<!-- 2, about interaction easier to see text, phont  -->
<!-- 3, narrative message, title, axis and ... -->