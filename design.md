---
title: outline
layout: default
---

<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

	- [tools](#tools)
	- [data](#data)
	- [applied neuroscience/experiments/use cases](#applied-neuroscienceexperimentsuse-cases)
	- [statistical science](#statistical-science)

<!-- /TOC -->

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

## tools



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


## data

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

note that we do not have any "vector" datasets per se right now, and not sure that we will, though we might.

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




## applied neuroscience/experiments/use cases

the outline is here: http://docs.neurodata.io/SIMPLEX/Reporting/reports/phase1/discovery.html

this is the least developed, and arguably least important for now.
that said, for each project, i would expect:

- manuscript
- analysis
- a figure
- a summary
- co-authors/contributors



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
