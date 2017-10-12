# cs1-twitter

## Overview
Did you know that the SIGCSE Symposium Twitter feed has tweeted about #sigcse_2015 more than any other topic in its last 2,000 tweets?  Or that Tiffany Barnes (SIGCSE Symposium 2018 Co-Chair) tweets most often about #csforall?  In this assignment, students have the opportunity to connect their Java programs in their favorite IDE to Twitter to determine some interesting information about the Twitter feeds of their choice.  

## Assignment Materials

* [Assignment handout](Twitter.doc)
* [Twitter starter code](Twitter_Driver.java)
*  [Twitter 4j properties file template](twitter4j.properties)
*  [Twitter 4j jar file](twitter4j-core-4.0.4.jar)
*  [File of common words](commonWords.txt)

## Meta Information

### Summary
The Twitter assignment teaches students how to connect their Java programs to a realtime data stream using a freely available API.  They have to apply what they've learned about string manipulation, sorting, ArrayLists, and finding the maximum value in a collection of items in order to achieve the goal of determining a Twitter user's most common non-common word they've tweeted in their last 2,000 tweets.  Aside from practicing the concepts mentioned above, I think the most signifcant outcome of this assignment is that beginning CS students have written a program to interact with other real-world programs, like Twitter.  Once they see how little code is needed to connect a program they create to a program like Twitter, my hope is that they will be empowered to explore other data sources without thinking that is out of reach.  

### Topics
Topics covered include string manipulation, ArrayLists, sorting, finding maximum value, method decomposition, understanding existing code, working with an unfamiliar API, and file I/O.

### Audience
CS1, early CS2

### Difficulty
Medium level of difficulty, with most students completing Parts I and II in 2 - 3 hours. Part III probably takes them 1-2 hours more.

### Strengths
* Integration of many CS1 principles
* Real world relevance => task for an intern => research tweets for a company

### Weaknesses
* There are 11 steps the students have to work through in order to verify that their program is linked to their Twitter account, providing several opportunities for students to misread or skip an important direction.  Since the main point of the assignment does not deal with getting Twitter up and running, I try to provide as much support as needed to get the students to the programming part as quickly as possible.
* Many high schools do not permit teachers to require students to make social media accounts outside the ones provided or supported by the school district.  If a student does not want to make their own Twitter account, I provide a flat file of tweets from a public Twitter feed they choose which they can use as an input file.  Students are still working with real Twitter data and are able to benefit from the assignment like their peers.    
* Twitter might be blocked on student workstations.  If so, I tell the students they can either work on the assignment at home or they can use the flat file that I described above.
* Even if students have written their output to a file before, some students find toggling between sending output to the screen or a file challenging.

### Dependencies
The assignment is written for Java, depends on Internet access (until you choose to use a flat file of tweets), and requires the setting of a classpath to incluce the required jar file.

### Variants
In Part II, students are asked to determine the most frequent non-common word that a person has tweeted in their last 2,000 tweets.  While Part II is the main part of the assignment, Part III is really where the gold is.  In Part III, students are asked to devise their own query to investigate something they find interesting using Twitter feeds.  They are to examine the Twitter 4J API to see what methods are available to them and then program their own query.  Examples include, but most definitely are not limited to:
* Filter your home timeline (these are all the tweets from people you follow) to avoid a particular term.  For instance, if you are an Android fan, you could filter out all tweets with Apple in them. 
* Count the number of tweets originating from your zip code that contain the word “flu" during a particular timeframe to see if a flu outbreak is happening in your area.
* Send tweets every 10 minutes to your friend on his/her birthday.  Use a timer.  
* Search for tweets in your zip code on a particular Sunday to count how many tweets there are containing the names of NFL teams to see which teams are most popular with residents in your zip code. 

### Contact
Ria Galanos<br>
[Thomas Jefferson High School for Science and Technology](http://www.tjhsst.edu)<br>
ria.galanos [at] gmail

