---
title: outline
layout: default
---

<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

	- [related sites](#related-sites)
	- [orgnaization thoughts](#orgnaization-thoughts)
	- [top of site](#top-of-site)
	- [data](#data)
	- [tools](#tools)
	- [applied neuroscience/experiments/use cases](#applied-neuroscienceexperimentsuse-cases)
	- [statistical science](#statistical-science)
	- [about/other](#aboutother)

<!-- /TOC -->


## related sites

2. http://www.alleninstitute.org/ is close collaborators and closely related
3. https://www.janelia.org/ are also close collaborators and closely related

i don't particularly like them, but their institutional goals are closely related to ours

## orgnaization thoughts

we have FOUR major "threads" in our work:

1. computer science
2. big data curation
3. statistical science
4. applied neuroscience

within each thread there are "projects".
each project within a thread has commonality within thread.

BUT, for the website, i think it probably makes sense to essentially have THREE threads:

1. data
2. tools
3. experiments/applications/use cases/results

this is because "statistical science" is essentially a set of ideas,
not particularly useful for users in a certain sense.


## top of site

one of my favorite sites is:  http://jhu.edu is beautiful, especially the switching movies in the background.

i could see using the movies [here](videos.md) as background movies on the top.

then, as you scroll down, you get to

1. data
2. tools
3. applications/use cases/experiments



## data

when scrolling down to data, i could image a couple things.

1. a matrix organized like http://neurodata.io/#browse, though with nicer pictures.  the downside of this is that it differentiates modalities,
2. an interactive graphic that looks something like this:
http://www.nature.com/neuro/journal/v17/n11/images/nn.3839-F1.jpg
but each box/point would actually be clickable, and correspond to a particular dataset. the axes could be resolution and volume, or something like that.

the above 2 ideas, however, in my head, are mostly for images,
not for any of the other kind sof data.

3. a link to search, while highlighting certain projects, somewhat like http://www.missionmedia.com/case-studies
then, which projects got highlighted could change every few months or something, as we got new projects.  
searching terms could include the data "type", species, etc.

4. data could be organized in the same fashion as "tools", eg:
   1. images
   2. time-series
   3. shapes
   4. graphs
   5. objects

 another option i am realizing is that we could have just 1 table after scrolling down:


 |   	| images  | time-series  | shapes  | matrices  | graphs | objects |
 |---		     |---|---|---|---| | |
 | data 	   |   |   |   |   | | |
 | store   	 |   |   |   |   | | |
 | explore   |   |   |   |   | | |
 | analyze   |   |   |   |   | | |


that you get when scrolling down, and clicking each "element" of the tale brings you to a (mobile compliant) pop-up showing the options within that.

and for example, clicking "shapes" pops-up an interactive graphic where each point/square is a different dataset (with axes being something like resolution and volume), or "graphs" has a similar interactive graphic (with axes being something like # veritces & # edges).



the list of all bigdata curation projects is here: http://docs.neurodata.io/SIMPLEX/Reporting/reports/phase1/datafication.html

we currently organize into:

- electron & light microscopy images (images, including time-varying images)
- annotation (shapes)
- magnetic resonsance (MR) graphs (graphs)

but if you look at http://openconnecto.me/graph-services/download/
you see that we have many other graphs, not just MR,
though i didn't have a particularly good way of getting the table together.

i imagine the "main page" for data could have options for browse/search, as well as highlight certain projects.  
ideally, search would enable filtering by data type (image, time-series, shape, graph, object), species, modality, etc., though this is not obviously in scope before SfN.

the current projects page: http://neurodata.io/projects
is obviously inadequate.


each data project typically has the following parts:

- visualize
	- images
	- graph (some images have corresponding graphs)
	- shapes (some images have corresponding shapes)
	- vectors (some images have corresponding vectors)
- manuscript
- media
- experiments/results
- tools (link to relevant tools)
- downloads
- some beautiful images
- a 1 sentence description
- license info
- coauthors/contributors

in theory, each project stores all the necessary metadata in our database, so, you could grab it with a URL.
for example, the bock11 dataset metadata is available here:
http://openconnecto.me/ocp/ca/bock11/info/



## tools

here, i imagine the above table, with each element being clickable, and bringing the user to a page/slide that has the contents listed in the H2 headers in skeleton.md


the list of all projects is available in slide form here: http://docs.neurodata.io/ndintro/cs.htm

and in outline form here: http://docs.neurodata.io/nddocs/cs.html

each cs project typically has the following parts:

- webpage
- code
- documentation
- API
- tutorials
- issues
- manuscript
- benchmarks
- installation/setup
- several "highlights" bullets
- an illustrative image
- coauthors/contributors

see here http://docs.neurodata.io/ndintro/cs.html#7 for some examples (slides are either cs projects or outline of slides).

in my head, the tools "main page", would contain a matrix of links, and each link would essentially go to (either in a new page or just there) something like the slide.  note that the slide only has a subset of the content listed above.

## applied neuroscience/experiments/use cases

the outline is here: http://docs.neurodata.io/SIMPLEX/Reporting/reports/phase1/discovery.html

not entirely sure what to call this section:
experiments, use cases, applications, model?

but, it essentially includes a list of results.
each result should have:

- manuscript
- analysis
- a figure
- a summary
- co-authors/contributors

not sure how to organize them: species? scale? modality? all options?

maybe in highlightable boxes organized chronologically?


## statistical science

the outline of the various projects is here: http://docs.neurodata.io/nddocs/stats.html
i haven't yet created slides for each of the projects, but they each many of the following features:

- manuscript
- arxiv
- figure
- 1 sentence summary
- code
- co-authors/contributors

like i said, it is not obvious that we need this.
my guess is that it would confuse the users


## about/other


i feel like this one is just a footer with links to basic pages
