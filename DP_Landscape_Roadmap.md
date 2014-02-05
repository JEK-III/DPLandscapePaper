
#What does “data publication” mean?
Generally agreed upon properties:
Available– now and for the indefinite future
Citable– a citation made now will work for the indefinite future

Up for debate:
Trustworthy– certified “good” by some community standard
For many, this means "peer review"

shared vs. published vs. Published [(Callaghan, 2012)][callaghan_making_2012]
available + citable + trustworthy.


#Why publish data?
* Bring data into the scholarly record.
* Enable reuse and encourage sharing.
Availablilty & Trustworthiness are good for reusers.
Citabitlity provides a mechanism to credit authors, encourages sharing.
also good for resusers to be able to specify exactly what they're reusing.

Help with the so-called 'reproducibility crisis' in science.
If it becomes the norm to publish the raw data underlying a paper, it'll be easier to spot honest mistakes and dishonest fudging / fabrication.

most data is lost [(Vines, 2013)][vines_availability_2013]

# What does a data publication look like?

There are a variety of ways to break this down, based on who is responisble for what.  
5 models of data publication [(Lawrence, 2011)][lawrence_data_2011]

For my purposes, I'll break it down into 3 models based on the type of documentation included

## Traditional article
Data published alongside a traditional journal article.
Example: Supplemental material, tables, whatnot, hosted by the journal publisher
[Journal of Neuroscience stopped publishing supplemental material in 2010][maunsell_announcement_2010]
Example: [Dryad][dryad] publishes the data underlying figures in traditional journal articles.
available and citable, any review is up to the journal
For some specific data types, deposition in appropriate databases has been the standard for a long time.
Example: nucelotide sequences are deposited in [GenBank][genbank], and protein structures in the [Protein Data Bank][protein_data_bank].

## Data Papers
Data published alongside a descriptive "data paper"
Everyone agrees on what they are not: results, analysis, or conclusions.
Currently, about half are dedicated data journals.  The other half publish multiple article types.
Examples of data journals: N [Nature Scientific Data][nature_scientific_data], [Geoscience Data Journal][geoscience_data_journal], and "metajournals" from [Ubiquity Press][ubiquity_press_metajournals]
Examples of journals that publish data papers: [F1000 Research][f1000_research], [Internet Archaeology][internet_archaeology], or [GigaScience][gigascience]
The number of journals publishing data papers is growing rapidly.
Most journals require the data to be in a trusted repository.  A very few handle it themselves.
All of these things have a component of 'peer review'

## Standalone ##
Here, the data is published without a related journal article.
There may be rich metadata, structured or unstructured, but there isn't a paper
Examples: [Open Context][open_context] and NASA PDS peer review data.
Example: [Figshare][figshare] makes data available and citable, but doesn’t validate it in any way.


# How does a data publication become Available, Citable, and Trustworthy? #

## Available
###Now
publish = 'make public'
you don't have to email the author.
As a practical matter, almost always means available over the internet, in a repository.
It is entirely possible to publish data to a limited access repository, analagous to a closed-access journal subscription.

Consider talking about versioning in here

###The Future
The idea of future access via preservation in Libraries, etc. has been baked into scientific publishing from the start.
In the digital era, it's more complicated.
In general, data can't be conisdered to be published unless it is deposited in a trustworthy repository.
Repositories come in two main flavors: institutional (Merritt, PURR) and disciplinary (GenBank, tDAR)

What makes a repository "trustworthy" is up to you.
On one extreme are [TRAC][trac_2007] certified repositories.  
However, certification is a complex and time-consuming process, only 4 repositories have done it
Other, less onerous certification scemes exist: Data Stamp, etc.
One can judge by the organization running the repository: government bodies and large universites might be trustworthy.  
(but the effect of last fall's shutdown on PubMed shows that they may not)

registries such as [re3data][pampel_making_2013] and [BioSharing][biosharing]
Sustainablility becomes a serious concern when you look out further than a decade.


## Citable ##
Total agreement: datasets should be formally cited in the reference list
Amsterdam manifesto[(FORCE11, 2013)][amsterdam_manifesto]
Consensus principles

### Simple case
Very good consensus: 5 element citation- creator(s), title, year, publisher, identifier
Corresponds to DataCite required metadata, TR DCI, CODATA report.
Familiar looking

### Deep citation	
Problem: if you only used part of a dataset, you may need/want to cite exactly the subset you used.
Hard to come up with a general solution that works for any kind of dataset
Solutions: describe in text, include date range or list of variables in citation.
Include some recommendations

### Dynamic data
Problem: unlike journal articles, many datasets change over time.
Two kinds of dynamic datasets that we have to think about: add-only and fully revisable
Solutions: add-on can have access date, date range, range of record IDs (whatever those are)
revisable can have version numbers
"time-slice" and "snapshot" from [DCC][dcc_guidelines]
Include recommendations 

DataCite recommends, but does not require that the object pointed to be immutable.
Find a counterexample

### Just-in-time IDs ###
Solution to both problems: the researcher citing the dataset mints a new ID to refer to whatever they want
Not clear exactly how this works.
RDA working group proposed one version of this.
Unresolved technical and policy questions: to the extent that an ID is a promise, how can you make promises about someone else's data?


## Trustworthy: How does data peer review work?
###Peer-review
Distinction can be drawn between technical and scientific review [][callaghan_making_2012]
Data and paper are generally reviewed together as a package.
An exception is GigaScience, which assigns a data reviewer for techncial review.
About half of data journals consider impact / novelty.
When guidelines are provided, they are roughly similar.
Example: NSD or any other
The process, however, is variable– ranging from traditional to postpublication experiments of F1000 Research.

Standalone
Open context provides a multi-tiered evaluation system (1-5).
* 3 technical review
* 4 editorial review
* 5 external peer review
NASA PDS does peer review in an in-person meeting

Experiments in peer review going on with articles could be relevant to data:
postpub review of data papers by F1000, etc.
3rd party review (libre, rubriq) not happening, but could be a way to make PR work for repositories

## Beyond data publication
Data as software: open source software community has confronted many problems related to sharing and collaborating.
Version control: it would be nice to be able to capture contributions from people who want to improve/clean up/work on/adapt a dataset.  versioning/forking could provide a model
Collaboration: lots of contributors, contributions tracked, attribution can be maintained

Unresolved issues:
VCS desgined for relative short text files, none of them handle huge or opaque file types well
Attribution– no standards for how much work has to be done on one or more existing datasets for you to be considered the 'author' of a new dataset.  This is a cultural rather than technological issue, and standards are likely to evolve differently for different disciplines.

Example: Open Context uses mantis bug tracker and GitHub

[amsterdam_manifesto]: http://www.force11.org/AmsterdamManifesto "Amsterdam Manifesto"
[data_seal]: http://datasealofapproval.org/en/ "Data Seal of Approval"
[dryad]: http://datadryad.org/ "Dryad"
[genbank]: http://www.ncbi.nlm.nih.gov/genbank/ "GenBank"
[geoscience_data_journal]: http://onlinelibrary.wiley.com/journal/10.1002/(ISSN)2049-6060 "Geoscience Data Journal"
[gigascience]: http://www.gigasciencejournal.com/ "GigaScience"
[f1000_research]: http://f1000research.com/ "F1000 Research"
[figshare]: http://figshare.com/ "Figshare"
[internet_archaeology]: http://intarch.ac.uk/ "Internet Archaeology"
[lawrence_data_2011]: http://projects.iq.harvard.edu/datacitation_workshop/files/lawea_datapublication_submitted.pdf "Data Publication"
[maunsell_announcement_2010]: http://www.jneurosci.org/content/30/32/10599 "Announcement Regarding Supplemental Material"
[nature_scientific_data]: http://www.nature.com/scientificdata/ "Nature Scientific Data"
[protein_data_bank]: http://www.rcsb.org/pdb/home/home.do "Protein Data Bank"
[callaghan_making_2012]: http://dx.doi.org/10.2218/ijdc.v7i1.218 "Making Data a First Class Scientific Output: Data Citation and Publication by NERC’s Environmental Data Centres"
[trac_2007]: http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.133.4630 "Trusted Repository Audit Checklist"
[ubiquity_press_metajournals]: http://www.metajnl.com/ "Ubiquity Press MetaJournals"
[vines_2013]: http://dx.doi.org/10.1016/j.cub.2013.11.014 "The Availability of Research Data Declines Rapidly with Article Age"







