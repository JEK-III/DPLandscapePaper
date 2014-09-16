# Revisions

* describe the undisputed center and maybe a few edge cases




###DP models

####Documentation
* Data has to be documented to be useful
* Difficult for people in your field, doubly difficult for someone from another field

* Frequently this is the most visible aspect of the publication
* Lawrence and ODE DP models both take this into account


* Can tie into the traditional scholarly literature
* e.g. documentation with a peer-reviewed paper.
* Relationship can be 1 paper, 1 dataset, but it can also be complex
* we're going to talk about three kinds of documentation


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
\cite{lawrence_data_2011}

**In general then, for our purposes, we define to Publish (with a capital P) data, as to make (as permanently as possible) data available on the Internet that has been through a process which means it can appear along with easily digestible information as to its trustworthiness, reliability, format and content.**


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
	

* metadata:
	* structured, structured-ish
	* GEO supports MIAME
	* 

###Conclusions
* summary
* suggested directions or immediate challenges to overcome
* call to action
* indications of things we should stop trying
* alternative perspectives
* What do the authors want us to take away from this paper?


Why are there different models and which approach is better for different situations?

* data papers were deliberately designed– ESSD started in 200X
* the others predate the idea of "publication" 
* *while new repositories often think about it, others have sort of wandered into it
* the others not so much
* hence the diversity of independent data publishers– different communities more or less ad hoc solutions to sharing data, some of which aspire to publication, some of which don't
* *although dryad and crap _were_ designed as publications
* *supplemental data also sort of just happened

* data papers kind of dominate the convesation
* therefore, this definition of data publication is a bit DP-centric

* critical thing is to ask what makes _publication_ different from sharing, release, all that other crap.
* otherwise, we're having a nice conversation about data in a totally different paper





Are these really the only three models in consideration or does the publication model overstate a consensus around a certain type of data publication? 

* although we think the models here are a useful way to classify/talk about data publications that reflects the current coversation, the reality is more complicated
* a dataset can have multiple relationships to multiple kinds of documentation– what is the publication?
* *not easy to fence in.



Why is there controversy in some areas?

* The aspects of data publication that are agreed on are the ones that are most similar to traditional papers. Wherever that paradigm doesn't suit data well, controversy erupts.
* *static, small datasets are handled relatively easily
* *dynamic data raises questions for both citation and validation
* *validation is generally more heterogenious; peer review is less directly adaptable to data than citation, say

* Diverse kinds of material are regarded as data by one research community or another and, while at least some aspects of publication apply well to at least some kinds of data, other approaches are possible.

* consequently, we have to be flexible in how we apply the idea

OR...

* In a 2013 paper\cite{parsons_is_2013}, Parsons and Fox argue that thinking about data through the the metaphor of print ``publication'' is in many cases misleading.
* The prsent a bunch of alternate metaphors. 
* *``big iron'', taken from industrial production might better describe projects like LHC or many things in astronomy

An alternative metaphor that seems to be gaining traction is ``data as software''\cite{schopf_treating_2012}.

In some cases, it may be better to think of releasing a dataset as one would a piece of software and to regard subsequent changes as analogous to updated versions.
The open-source software community has already developed many potentially relevant tools for working collaboratively, managing multiple versions, and tracking attribution.
Ram (2013)\cite{ram_git_2013} catalogs a multitude of scientific uses for the software version control system \href{http://git-scm.com/}{Git}, including data management.
Open Context uses Git and \href{http://www.mantisbt.org/}{Mantis Bug Tracker} to track and correct dataset errors.

* Dat

Furthermore, projects such as \href{http://ipython.org/notebook}{IPython Notebook} integrate data, processing, and analysis into a single package.
However, scientific software struggles for recognition\cite{pradal_publishing_2013} just as data does, so using it to alter or affect the academic reward system for data is a tricky prospect.

* Ecosystem metaphor
* lots of approaches are good
* don't know where we are yet.
Ultimately, while ``data as software'' is promising, data is not software.
Nor is it literature. 
The prestige and familiarity of terms like ``publication'' and ``peer-review'' are powerful, but we may have to stretch their definitions if we are determined to apply them to data.

* current models probably won't last, we should be prepared for new stuff



####Availability
* gotta be in a 'trustworthy' repository
* no totally agreed on standard for what that is


####Citability
* basic+ can handle _a lot_ of data
* but not everything
* probably the format of the citation should suit the situation: keep it as simple as possible to precisely 

####Validation
* lots of possible approaches
* let's not get boxed in




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


Diverse kinds of material are regarded as data by one research community or another and, while at least some aspects of publication apply well to at least some kinds of data, other approaches are possible

In practice, availability is usually satisfied by depositing the dataset in a repository, citability by that and assigning a persistent identifier (e.g. a Digital Object Identifier, or DOI), and validity by peer review.


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