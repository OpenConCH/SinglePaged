This document: https://bit.ly/2MU3Ff3

# OpenCon Switzerland 2018: second day, tools workshop

present:

- Julien Colomb • [@j_colomb](https://twitter.com/j_colomb)
- Tim Head • [@betatim](https://twitter.com/betatim)
- Achintya Rao • [@RaoOfPhysics](https://twitter.com/RaoOfPhysics)
- Vicky Rezzonico • [@ViRezzonico](https://twitter.com/ViRezzonico)
- Malin Ziehmer • [@malinziehmer](https://twitter.com/malinziehmer)
- Sinan Teske • [@NanisTes](https://twitter.com/NanisTes)
- [Francesco Varrato](mailto:francesco.varrato@epfl.ch)
- [Sarven Capadisli](http://csarven.ca/#i) • [@csarven](https://twitter.com/csarven)
- [Emilian Capadisli](http://emilianc.info/#i)
- Julieta Arancio • T: [@cassandreces](https://twitter.com/cassandreces) • GH: [@thessaly](http://github.com/thessaly)
- Joao Martins • [@rambujo](https://twitter.com/rambujo)
- Amani Said

# Principles

* Interoperable - using open Web standards
* Decentralisation
* Accessibility
* Portability
* No vendor-locking


# Proprietary software used at the moment

Atlassian tools (Confluence, Jira, HipChat)
Google Drive (Google Docs, Spreadsheets, Photos, Gmail)


# List of tools for Open Science

Service to compare tool alternatives: alternativeto.net

List of lists:
* 101innovations.wordpress.com (not only open source, the data is in the google doc: 
* [400+ Tools and innovations in scholarly communication](https://docs.google.com/spreadsheets/d/1KUMSeq_Pzp4KveZ7pb5rddcssk1XBTiLHniD0d3nDqo/edit)
  * Mostly non-interoperable / vendor lock-in.
* github alternatives: itsfoss.com/github-alternatives
* [Open Science MOOC](opensciencemooc.eu/modules) has interesting tools in module 5
* Skype alternatives: opensource.com/alternatives/skype (more are at opensource.com/alternatives)

Authoring articles, annotations, notifications:
* [dokieli](dokie.li) (source: github.com/linkeddata/dokieli)

Slack replacements: 
* [Mattermost](mattermost.com) -- self-hosted
* [Gitter](https://gitter.im/)

Github replacements:
* [git](git-scm.com), the basic versioning protocol on which github is build
* [ownCloud](owncloud.org) (?) + docker + git local deployment
* [nextCloud](nextcloud.com) 
* [gitlab](gitlab.com), paid and less user-friendly
* [RopenSci](ropensci.org/), for R packages
* [rsync](rsync.samba.org), incremental file transfer tool
* [Sourcetree](www.sourcetreeapp.com)
* [TortoiseGit](tortoisegit.org)

MS Office replacements:
* [OpenOffice](openoffice.org)
* [LibreOffice](www.libreoffice.org)
* 

Google Docs alternatives:
* [sandstorm](sandstorm.io), open source platform for self-hosting web apps
* [hackmd](hackmd.io)

Web search alternatives:
* [DuckDuckGo](duckduckgo.com)

Research publishing platforms:
* [F1000](f1000research.com)
* 

[JROST](https://jrost.org)





# to notice !!!

The most important is to see if the data produced is portable into a different format/software. Ex.: Mendeley.

For many tools, even if they are open-source, you are stuck because the data can not be taken out and imported elsewhere.

see:
[https://www.w3.org/wiki/LDP_Implementations](https://www.w3.org/wiki/LDP_Implementations)

When choosing the tool, you should think about the format of the data produced and how it can be downloaded and ported to other tool.

This "ultimate tool" often does not exist, but you need to be know where you are going into.
Even if you have the "ultimate tool" and lose track of the finality or nobody uses it, then the tool is useless.

# working open with Git github/gitlab

- gitlab can run locally (github too in theory, but most too expensive)
- If for political reason you cannot use github, use gitlab. But you need to have someone to look after it. Otherwise, use github.
- Github has a stonger community
- Shouldn't ignore the archiving of one's code/data. Don't rely on one service. Git is "Distributed" VCS, so you can push to multiple sources.


# collaborative document editing
## alternatives to gdocs 







---
# Workflows for open science 

# Ideas
- Overview of tools in a open access graph similar to https://graphcommons.com/ technology behind this is [neo4j](https://neo4j.com) --> tranfering the 400+ tool into a explorable graph.
- To have a real *open alternative* to a tool should also mean to has some certainty that the organization behind the open tool will be around in 10 years from now. Or that open tools run over shared protocols that will be supported in the long term.
- 

## Choosing a tool checklist
- Which open standards is it using?
- What are the privacy implications?
- How accessible is it for different uses?
- Can I export the information/data we are generating
- Are we able to work collaborative



## Tasks for which we are looking for tools

- how can I share my data
- what should I use for versioning
    - git as a tool to version work, GitHub to share those versions with others
- are there any specific tools which help me in working in a reproducible way
- how do I present my work (reproducible presentations instead of copy-paste into PowerPoint)
    - https://github.com/gnab/remark/blob/develop/src/remark.js which lets me make text files that I can copy&paste into new presentations
    - https://github.com/RaoOfPhysics/201804_PCST
        - Presentation available https://raoofphysics.github.io/201804_PCST/#/
        - Built from `.Rmd` containing presentation text and code for generating plots
        - Three levels of use, documented here: https://github.com/RaoOfPhysics/201804_PCST#instructions-for-working-with-the-raw-files
- collaborative writing of papers
    - hackmd
    - authorea
    - sharelatex
- reproducibility
    - could you expand this point?
- are there any open tools that already became a standard?
    - git
- Is there something like a basic toolkit which we could recommend to newcomers in coding etc.?
- related to Tim´s comment on how little programming students learn while studying: what recommendations can we give as a starting point? (relates to the point mentioned before on a basic toolkit)?
    - https://carpentries.org/ as a source of training as well as recommended tools by looking at what they teach
- tools for active research data management (similar to ELNs, LIMS etc.); how can I easily annotate, store and sort my data, metadata and protocols in a handy way
    - what is a ELN or LIMS? ELN=Electronic Laboratory Notebooks (instead of old-school paper notebooks), LIMS=Laboratory Information and Management System, both things being helpful on the way to reproducibility, most often used in Life Sciences. Some say that LIMS are overkill (too much options, too expansive) for life science.
- Tools should have labels to track andeasily assess their openness: ideally, it should be a standard body, not a private company


# On the importance of learning digital tools

We have all spent so much timuch time learning maths, we could also take some time to learn how to use computers (= new tools)

Any idea how can get this more into teaching? Currently we try to get research data management to be established in the students´curriculum, so how to get more programming into the curriculum. Who to approach, how to reach out, also to communities and disciplines that are not so much into programming yet.

- software carpentry, data carpentry 
- free-lance workshop creators (access2perspectives.com: 1000€ a day for 12 students in general)
- co-learning: see meetup.com: R-ladies,...
- there are also some train the trainer programs (FOSTER for example)

It will take some time for this to get into curriculum, how do we incentivize (?) people during this transition to acquire these skills?

- For data management, see (and contribute to) [this open ooooooproject who collects and creates outreach material](https://rdmpromotion.rbind.io)

The carpentries are an option but still it has to come from someone hyper motivated.

That is exactly the point; it would need an immediate initiative to implement programming even more in the curriculum; my feeling is that no one really feels responsible for it...Is it the professors taking this over, the assistants or even student initiatives?

I don't think it's a matter of responsibility, but of which are the standards around, what everyone is using, what is indeed useful and easy. That's why -going back to Sarven's point- I think mainly point should be educating in the *criteria* rather than the tools. If pedagogically the tools are more appealing, then these tools have to be very well-chosen, taking in account these criteria.

Criteria would be a great way to also help professors transfer knowledge!

And to include professors that not necessarily come from the tech world, because it's not a 100% tech discussion.

And these criteria could also include a checklist on how to choose a tool, depending on your needs (e.g. thinks you need to consider before choosing a tool, as discussed befpore).

