This newsletter/update written primarily @calben on 2014 06 25  

# Data Management

Some solutions have been explored (implemented) for data management, which I will describe starting from frontend going to backend.

## Grafana

To view data, there is a new graphing dashboard, Grafana, that is proving to be an excellent option.  Grafana is great because it's just an entirely client-side javascript, css, and html project.

### Important Features

+		Grafana provides a *really* sick dashboard.  Fast rendering, multiple axes, annotations... creating and editing dashboards.  Prepare to fall in love.
+		Has an expression parser.  It's slightly incomplete for InfluxDB, but it's getting there and we can help!

### Improvements to Implement

+		Grafana is not quite mobile friendly.  I'm working on making the navigation bar work correctly with mobile devices but there are some deeper issues including making charts present correctly on mobile.  We don't necessarily need to be able to edit charts from mobile, but being able to view them perfectly from a phone or tablet seems immensely important to me.
+		Grafana provides excellent viewing capabilities but no interactive capabilities- no way to send messages to actors.  A panel needs to be built that can run alongside Grafana to send messages to houses.
+		A dude has already made a dropdown menu to choose from one of many Bootswatch themes.  It's the bootswatch theme selector and can be viewed here: http://wdtz.org/bootswatch-theme-selector.html.  Given that Grafana is themed with Bootstrap, it could be cool to add this to Grafana.  Not really necessary... at all, but it would be a nice tweak.
+		Grafana isn't yet optimised for InfluxDB, which is to say it doesn't entirely support InfluxDB.  If you look at the issues pages for Grafana and InfluxDB, you'll see a couple new issues I've made that start poking into the problems.

`
This is a commment
- @calben
`

## InfluxDB

### Important Features

+		Distributed.
+		Time series.
+		Database.
+		... not much else to it really.  Chosen for being new, seemingly reliable, and written by people who *really* know what they're doing.

### Improvements to Implement

+		If we can extend InfluxDB with an optimised time series image database, that would be really awesome.

## ElasticSearch

### Important Features

+		Mostly using this to support custom dashboards on Grafana.
+		Also supports an incredible number of other features that you can find on the website for Elastic Search.

### Improvements to Implement


## Stuff We Still Need

+		There doesn't seem to be much out there in the way of open source image databases.
+		


Sensors
-------

Sensors are still in development by Sensorica with Tactus Technology.  I'm honestly not entirely sure 


Legal
-----

I will be meeting with legal counsel from McGill about the following topics::

1.		Student intellectual property protection for undergraduate research projects.
2.		Methods of going about the division of property between researching groups, in our case how to ensure HyveDev's stuff can be clearly separated from Canmet, Natural Resources Canada, and Sensorica in our potential join endeavour.
3.		 



HyveDev Public Update
=====================


