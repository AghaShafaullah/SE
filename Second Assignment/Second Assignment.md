# Cheating Death: A Statistical Survival Analysis of Publicly
* **Available Python Projects**
* **Rao Hamza Ali, Chelsea Parlett-Pelleriti,Erik Linstead**
* **{raali,cparlett,linstead}@chapman.edu**
* **Machine Learning and Assistive Technology Lab**
* **Chapman University**
* **Orange. CA. USA**		

# Introduction:-
Open Source Software (OSS) projects are ubiquitous in today’s software landscape and provide a rich set of data on which to analyze facets of the software development process using everything from additional statistics to deep learning. Open Source development efforts typically have a single person or body that selects a subset of developed code for build releases and projects are maintained by a decentralized team of developers, who with low organizational cost, are able to produce application that are at times used by millions. There is a weekly pattern of code update and addition.

# Methodology:-
Survival analysis is a statistical methodology used in biostatistics to study the duration of the life of an entity. The approach is based on measurements of events that occur at any time during a study.

# Example:-
The event of interest as developers who slopped contributing often some time, and use it to study the effects of developers droping any  on the health of a project. Any used commits by new developers as their event, to analyze the effects of introduction of buggy code to a software repository. For this study, we define the event of interest as the event of repository abandonment as complete lack of activity.

# Result:-
We use the following attributes of a project as estimators of survival rate over time.
* majoReleases whether releases were published by the project developers
* hostType type of hosting service used for the project repository
* authorCount total unique developers that have committed a revision to the repository
* multipleRepositories whether the project is hosted on multiple version control systems
We now discuss the results of running K-M curves and fitting Cox Proporitional-Hazard models on the data.
