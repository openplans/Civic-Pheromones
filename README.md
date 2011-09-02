Easy info sharing about community projects.

* Jose has an account on ioby.org, but his local rooftop farm decides to launch their campaign on Change By Us...
* Frank finds out about public meetings on bike lanes from  BikeBlog, but the editors don’t know about the Flatbush meeting tomorrow, so he misses it...
* Emma follows a list of environmental groups, but the maintainer of the list goes to grad school...
* City Groups launches in Boston, but so does Yelp Community Edition...

Civic Pheromones are simple data feeds from civic websites. Pheromones transmit various useful pieces of information:

* where a project is based (geography)
* what’s going on (meetings, events)
* what the project does (topics, activities)
* where to find out more (blog, twitter, contact details)

There’s no “there” there for Pheremones. No new website to follow. Civic Pheromones are invisible. They’re all about transmission of useful information from existing sources. We want to strengthen existing civic sites and reduce the silo-effect as new ones emerge. 

Tell me more
================

To make pheromones useful, we need some publishers, and some aggregators. Here is a use case:

1. myCommunityProject.org is a community-building website for neighborhood projects. It lists projects led by local residents. 
1. Jenny starts a local composting project, maintaining a drop-off site in the yard of a high school. She creates a project profile, including a map of the drop-off location.
1. Unbeknownst to Jenny, myCommunityProject.org has built-in Pheromone support. Her project is smelly.
1. Jenny lives in a small town, and there's one decent blog tracking environmental activism. The blog includes a sniffer for pheromones. The blog smells Jenny's composting project.
1. The blog's map includes the composting project, using the info conveyed in the bundle of pheromones.
1. Victor moves to the area. He looks at the blog map, and finds Jenny's project.
1. More composting takes place!

So what's actually going on?

* the first website has a Content Management System, so they add a plugin to automatically general pheremones from the existing project database, including a timestamp for last update, etc. 
* the plugin publishes a machine readable feed of all projects, in JSON
* the blog uses a different CMS, but there's a plugin for it too.
* their plugin fetches the feed, checks it for updates, and updates the map as needed.

How did the blog know about the feed? Feed discovery sites (like CityGoRound).

Let's get smelly!
==================

Big sites with their own APIs are all set.

Existing project with no way to publish data need help. They need plugins or modules for their current publishing systems. 
Bloggers need widgets.
And there's a whole world of apps and maps that can be built on these data feeds.


Sites that could be pheronominal!
=================================

Publishers 

* Change By Us http://nyc.changeby.us/
* ioby http://ioby.org
* City Groups http://citygroups.org
* Neighborland http://neighborland.org/
* SpeakUpNY
* other listings of civic orgs
* active civic orgs

Aggregators

* Oasis NYC
* all of the other publishers (break down those silos!)
* news outlets 


Background reading 
==================
+ Open311 http://open311.org
+ Ether, a transparent medium that supports the transfer of essential information about community-led projects. http://opensourceplanning.org/2011/06/ether/
