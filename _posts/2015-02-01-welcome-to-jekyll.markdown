---
layout: post
title:  "Welcome to R with Faye!"
date:   2015-02-01 14:13:07
categories: Intro
---
I first began learning 'R' in July / August (2014) time frame as a project for my business. 
Since, then I've made it a priority to learn 'R' in a more structured way, through various books and online courses.

Here are a few of my top resources.

## Blogroll##

[R bloggers][Rbloggers] a blog with many contributors from the R community.

[Simply Statistics][SimpStats] three biostatistics professors (Jeff Leek, Roger Peng, and Rafa Irizarry)

##Online learning##

[Data Science Specialization][Coursera] from Coursera / John Hopkins

[Data Science and R training][Datacamp] subjects from [Datacamp.org][Datacamp]


##Books##

* Advanced R by Hadley Wickham
* The Art of R programming by Norman Matloff
* R Graphics Cookbook by Winston Chang 


##Favorite CRAN libraries##

* magrittr
* dplyr

---

   >
   >
   >   
   


{% highlight R %}
library(magrittr)
suppressMessages(library(dplyr))

summaryFrame <- dataFrame %>%
	select( var1, var2, var3) %>%
	group_by(var3) %>%
	summarize(var1) %>%
	head(.)
{% endhighlight %}


[Coursera]:   https://www.coursera.org/specialization/jhudatascience/1?utm_medium=listingPage
[Datacamp]:   https://www.datacamp.com/courses
[Rbloggers]:  http://www.r-bloggers.com
[SimpStats]:  http://simplystatistics.org
