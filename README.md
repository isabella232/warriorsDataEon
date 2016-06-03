# warriorsDataEon
Warriors Data Visualization with Twitter Stream and EON.JS

As a lifelong Warriors fan in awe of their record-setting 2016 season and journey to the finals (which began June 2!), I wanted to make sense of incoming Warriors data. I wondered how game happenings would translate in realtime to Twitter (and, consequently, to a visualization.) This demo's chart, built with <em>EON.js</em> and the PubNub Twitter Stream, was fun to build, and in part because PubNub just makes it so easy to see what is happening up-to-the-second.
<h1>Project Overview</h1>
The data visualization of this demo has two main components.

<ul>
<strong><ol>PubNub Twitter Stream</ol></strong>
	<li>The <a href="https://www.pubnub.com/developers/realtime-data-streams/twitter-stream/">Twitter Stream</a> provides a good sample of tweets, reflecting the thoughts and emotions of users. This visualization uses the Twitter Stream to pull tweets that contain keywords about key Warriors players; it also looks at tweets with hashtags of the Warriors and their opponents (in this case, the Cleveland Cavaliers), to deduce which team’s fans are tweeting more.</li>
</ul>

<ul>
<strong><ol>Project EON</ol></strong>
	<li><a href="https://www.pubnub.com/developers/eon/">Project EON</a> is an open-source framework for the chart that makes a chart with the data from the Twitter Stream in this tutorial. There are many different ways to visualize the data: bar, gauge, spline, and pie (which is what is used in this tutorial), and numerous ways to customize the visualization. Project EON simplifies that process, and, with the EON chart builder, you may not even have to write any code!</li>
</ul>
