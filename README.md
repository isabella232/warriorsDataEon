## Visualizing Realtime Warriors Twitter Data using EON.js

<img src = "https://cloud.githubusercontent.com/assets/8932430/15787246/0dc85796-2976-11e6-9d79-fe698f1ccb90.gif"></img>

As a lifelong Warriors fan in awe of their record-setting 2016 season and journey to the finals (which began June 2!), I wanted to make sense of incoming Warriors data. I wondered how game happenings would translate in realtime to Twitter (and, consequently, to a visualization.) This demo's chart, built with <em>EON.js</em> and the PubNub Twitter Stream, was fun to build, and in part because PubNub just makes it so easy to see what is happening up-to-the-second.
<h1>Project Overview</h1>
The data visualization of this demo has two main components.

<ul>
<strong><ol>PubNub Twitter Stream</ol></strong>
	<li>The <a href="https://www.pubnub.com/developers/realtime-data-streams/twitter-stream/">Twitter Stream</a> provides a good sample of tweets, reflecting the thoughts and emotions of users. This visualization uses the Twitter Stream to pull tweets that contain keywords about key Warriors players; it also looks at tweets with hashtags of the Warriors and their opponents (in this case, the Cleveland Cavaliers), to deduce which team’s fans are tweeting more. Extracted tweets should look something like this: </li>
</ul>
<img src = "https://cloud.githubusercontent.com/assets/8932430/15787335/af50d12e-2976-11e6-9921-c1f3999c876e.png"></img>

<ul>
<strong><ol>Project EON</ol></strong>
	<li><a href="https://www.pubnub.com/developers/eon/">Project EON</a> is an open-source framework for the chart that makes a chart with the data from the Twitter Stream in this tutorial. There are many different ways to visualize the data: bar, gauge, spline, and pie (which is what is used in this tutorial), and numerous ways to customize the visualization. Project EON simplifies that process, and, with the EON chart builder, you may not even have to write any code!</li>
</ul>

<img src = "https://cloud.githubusercontent.com/assets/8932430/15787232/fd39a7b8-2975-11e6-9b00-4b823fe483b7.png"></img>

<p>This visualization will look much different (most likely no tweets at all!) if it is not basketball season. It runs best on a game day, or the day after a game. Want to take this visualization further? Some possible ways to get started: </p>
<ul>
	<li>Other teams or sports: this could be redone for the Giants, the Sharks, for the Olympics, etc.</li>
	<li>Election: Check political hashtags, candidates, and see what is being said about them.</li>
	<li>Machine Learning: I tried to predict who was winning or who had just scored, but it was, for the most part, inaccurate. There were so many conflicting contributing factors, but would be interesting to try to predict who would win, or to make a better algorithm to guess that.</li>
	<li>Web scraping. ESPN made their API private, so getting their live scores is much more complicated now.</li>
</ul>
<p> Questions? Made a similar visualization? I want to hear about it! Find me on <a href = "http://www.twitter.com/lizziepika"> Twitter</a>. </p>
