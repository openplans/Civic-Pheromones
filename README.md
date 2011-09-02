Why Civic Pheromones?
====================

* Jose has an account on ioby.org, but his local rooftop farm decides to launch their campaign on Change By Us...
* Frank finds out about public meetings on bike lanes from  BikeBlog, but the editors don’t know about the Flatbush meeting tomorrow, so he misses it...
* Emma follows a list of environmental groups, but the maintainer of the list goes to grad school...
* City Groups launches in Boston, but so does Yelp Community Edition...

Pheromones are useful messages
-----------

Civic Pheromones are simple data feeds from civic websites. Pheromones transmit various useful pieces of information:

* where a project is based (geography)
* what’s going on (meetings, events)
* what the project does (topics, activities)
* where to find out more (blog, twitter, contact details)

There’s no “there” there for Pheromones. No new website to follow. Civic Pheromones are invisible. They’re all about transmission of useful information from existing sources. We want to strengthen existing civic sites and reduce the silo-effect as new ones emerge. 

What's the process?
--------------------

To make pheromones useful, we need some publishers, and some aggregators. Here is a use case:

1. myCommunityProject.org is a community-building website for neighborhood projects. It lists projects led by local residents. 
1. Jenny starts a local composting project, maintaining a drop-off site in the yard of a high school. She creates a project profile, including a map of the drop-off location.
1. Unbeknownst to Jenny, myCommunityProject.org has built-in Pheromone support. Her project is smelly.
1. Jenny lives in a small town, and there's one decent blog tracking environmental activism. The blog includes a sniffer for pheromones. The blog smells Jenny's composting project.
1. The blog's map includes the composting project, using the info conveyed in the bundle of pheromones.
1. Victor moves to the area. He looks at the blog map, and finds Jenny's project.
1. More composting takes place!

So what's actually going on?
--------------

* the first website has a Content Management System, so they add a plugin to automatically general pheremones from the existing project database, including a timestamp for last update, etc. 
* the plugin publishes a machine readable feed of all projects, in JSON
* the blog uses a different CMS, but there's a plugin for it too.
* their plugin fetches the feed, checks it for updates, and updates the map as needed.

How did the blog know about the feed? Feed discovery sites (like CityGoRound).

Let's get smelly!
==================

Big sites with their own APIs are all set.

Existing project with no way to publish data need help. 

They need plugins or modules for their current publishing systems. 

Bloggers need widgets.

And there's a whole world of apps and maps that can be built on these data feeds.


Sites that could be pheromoninal!
----------------------------

Publishers 

* Change By Us http://nyc.changeby.us/
* ioby http://ioby.org
* City Groups http://citygroups.org
* Neighborland http://neighborland.org/
* SpeakUpNY
* other listings of civic orgs
* well organized civic groups

Aggregators

* Oasis NYC
* all sites publishing lists of civic engagement projects (break down those silos!)
* news outlets 
* volunteer coordinating websites

Do you have a secret agenda?
============

Why, yes! Despite great advances in ways to report issues and availability of data about infrastructure, it's really hard to find out what is going to happen on a particular block in the future. _Process_ is opaque. Cities and DOTs should be publishing all their process information, to support better engagment over the life of a project, and day to day interaction with the latest news - from early planning to shovels in the ground. 

So the not-so-secret agenda here is to start with civic groups, who may have an easier time trying new things out. As the aggregation tools become more powerful and useful, cities will see the benefit of signing up. 

Eventually, all agencies which either manage physical infrastructure or development projects on public property, or review development projects on private property, publish a simple feed of project data including the locations of projects, information and photos, and public input opportunities. The agency’s existing workflow systems automatically create these feeds. 

Meanwhile, many applications on the Web access this data and display it in useful ways, just like GTFS transit data has done for trip planning. An agency website can show all the agency’s plans and projects in map or calendar form. A neighborhood blog or local citizens’ group could embed on their site a list of projects going on in that neighborhood. A news site could use the feed to be sure they don’t miss something their readers would like to know about. We'll be immersed in useful, actionable data about civic and government activities.

Background reading 
==================
+ Open311 http://open311.org
+ Open211 http://open211.org
+ Ether, a transparent medium that supports the transfer of essential information about community-led projects. http://opensourceplanning.org/2011/06/ether/
