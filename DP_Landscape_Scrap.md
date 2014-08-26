# Revisions

###DP models

####Data publication pyramid
\cite{reilly_report_2011}

* 4 tiers, 5 models
* we're dealling with the middle two tiers here
* Processed Data & Data Representations
	2. Data resides in supplementary files added to the journal article
* Data Collections and Structured Databases
	3. Data resides in Community-endorsed Public Repository with bi-directional linking to and from articles
	4. Journals dedicated to so-called Data Publications only
* 2 & 3 fit into our category I
* 4 is our category II

####Lawrence sceme
1. Standalone Data Publication 
2. Data Publication by Proxy 
3. Appendix Data 
4. Journal Driven Data Archival 
5. Overlay Publication

* Category I covers
* *appendix data
* *journal driven data archival
* *data publication by proxy
* Category II covers
* *overlay publication
* Category III covers
* *standalone publication

* publication by proxy is complicated: refers to thing like the NAR database issue. could reasonably go with category II also

####Callaghan
* logically separate: we're only worrying about published and Published here, and the difference is validation, which we don't talk about.


###Independent publication
* to some degree any open repository counts; pretty much any could in principle serve to host data for type 1 or 2 publication
* lots of different approaches, lots of different ways to break these down:
	*Operator: government, academic instiutuion, private publisher
	*Focus: anything, data type, community around topic, community around place
		*ICPSR - discipline (social science)
		*Flybase, SGD, WormBase - research community (model organism)
		*Find a neuro thing - research community (subject)
		*
		
	*Combinations:
	






#Scrap sentences
With respect to Lawrence's scheme: data that supplements a paper covers \emph{journal driven data archival} and \emph{Appendix Data}.
Data that is the subject of a paper describes \emph{Data Publication by Proxy} and \emph{Overlay Publication}, and independend data corresponds to \emph{Standalone Data Publication}.\cite{lawrence_data_2011}
ODE includes a model that we don't: \emph{Data contained within peer reviewed articles} describes the usually highly reduced data presented in the figures and tables of a traditional article.
Data that supplements a paper describes both \emph{Data resides in supplementary files added to the journal article} and \emph{Data resides in Community-endorsed Public Repository with bi-directional linking to and from articles}, depending on the location of the data.
\emph{Journals dedicated to so-called Data Publications only} is contained within our data as subject category, although that also contains data papers from non-dedicated journals.


The key aspect of a citation here is that it can be used to identify and locate the dataset from now into the indefinite future; assignment of a persistent identifier like a Digital Object Identifier (DOI) is the usual way to accomplish this.

Science publishing had baked into it the notion that access must persist into the future for the use of future researchers.
Preserving access to print journals has long been the job of the library, but that's changing like everything else.  

A dataset that can only be accessed with a paid subscription or after accepting a use agreement can be said to have been published, but one that is provided by its creator over email is not.
The status of a dataset located on a researcher's personal website is not entirely clear.

However the real value and correctness of the work emerges later, as it's read and expanded on by the relevant community. 

% To break validity down further, Callaghan\cite{callaghan_making_2012} draws a useful distinction between technical and scientific validity.
% Technical validity– that a dataset has no inappropriately missing or out of range values, that the metadata is complete, etc.– is guaranteed by most data publishers. Scientific validity– that a dataset was collected using appropriate methods and holds scientific interests– is not always part of a data publication.


Parsons and Fox (2013)\cite{parsons_is_2013} argue that the metaphor of ``publication'' is limiting, and only suited to some datasets. 
They identify a number of analogies other than scholarly communication that might apply to data, including industrial production, cartography, and the World Wide Web.
They also make reference to an analogy that seems to be gaining momentum: data as software.\cite{schopf_treating_2012} 

Under this metaphor, publishing a dataset is analogous to a software release, and subsequent changes are analogous to new versions.
The open source software community has already confronted many of the problems associated with data (managing versions, sharing, collaboration) and developed tools and approaches to address them.
Open context came to use Mantis bug tracking software and Git out of practical concerns.

\cite{ram_git_2013}
\cite{chen_close_2014}

There are still issues to address.
Current version control systems, such as Git, are designed for code (relatively small text files), not large and variegated datasets. 
Attribution for derived datasets is not clear, but that's likely to be a cultural issue.

#Scrap thoughts

###what do I really want to say about availability?
Have to provide consistent access without a human gatekeeper
Consistent means into the future.
Your website is not a good way to do this.
In practice, you need to publish from a repository.

What are the characteristics of repositories that matter?
-IRs, discipline specific, and new deals like figshare and dryad
-preservation, access, discovery
-preservation = "tustworthy" TRAC, Data seal of approval etc.
-access = open or semi-restricted.
- -handling sensitive data
-discovery
- -discipline specific are good for this
- -IRs and other are wildly variable

###consider Open Context vs. tDAR 
as an illustrative example

###Beyond DP: what do I want to say about that?

* Parsons & Fox
	* multiplicity of metaphor
		
* A particularly promising metaphor is software production
* *lots of tools for collaborative work, sharing, attribution already developed by open source movement
* *Scientists can use Git (ram), although it's not great for big datasets
* *Increasing integration of data, analysis, and methods in iPython notebooks and RopenSci
* *Open context uses mantis and git to handle data problems like software bugs
* *However, scientific software, like data is struggling for credit, so that won't help us there.

* Circle back to P&F
* *Suggest taking pieces of other metaphors
* *take what we want from publication, be careful not to take what we don't want
* *data isn't a paper or software.  