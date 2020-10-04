# Cheating Death
	(A statical survival analysis of publicaly available python projects)


## Authors: Rao Hamza Ali,Chelsea Parletpellipriti,Erik Linstead
Links:[Visit to Webpage](chrome-extension://oemmndcbldboiebfnladdacbdfmadadm/http://www1.chapman.edu/~linstead/aliMSR2020.pdf)

# _Introduction and Motivation_ :
For the analyzing software development process using everything from traditional statistics to deeplearning.Every healthy project needs a team of dedicated developers and a set line of goals and achievements,These projects alsi need to be popular enough to gain intrest from potential volunteers when developersare excited about the project and the end goals.
### Goals:
How it is possible to see a project has performed overtime the health of project could be computed the number of contribution.
How frequently big targets met by the developers?
How focused the team is on making the software ready for distribution?
## __Research Methodology__:
	Developers work on this project as an volunteers.They wants to ensure their contributions do not go into a project that might endup inactive.

* Vc's(Version Control System) They used to host their projects.

* Having a project on multiple Vc's or repositories like PYPI and Debian Highlights.

* Survival analysis,Commonly used in medical studies to predict treatment efficiancy to find the probability of survival of popular open source projects overtime using kaplan-Meier survival analysis,and quantity the effects of these variables.

# _Results_:
following attributes of a project as estimators of survivalrate over time:
* MajorReleaseswhether:  releases  were  published  by  theproject developers
* HostTypetype of hosting service used for the project repos-itory
* AuthorCounttotal: unique developers that have committeda revision to the repository
* multipleRepositorieswhether: the project is hosted onmultiple version control systemsWe now discuss the results of running K-M curves and fittingCox Proporitional-Hazard models on the data