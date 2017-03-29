#### Q:  I'd love to hear more about how you see DaMaHub integrating into day-to-day work patterns.  I'd love to see some community consensus within the research data space around: 
* _posix-friendly, git-like workflow for research data (the dat project, git-lfs and to some extent the new ipfs-pack address this but none are ideal);_
* _self-describing data packages (hence the interest in research objects, datapackes.json, etc.). I assumed DaMaHub was a separate system from ODR, aimed more at a) above. Is that correct or are ODR and DaMaHub one and the same at present?_

A: ODR is a prototype for the public part of the DaMaHub system. The private part that allows private data sync, versioning, meta data management and commenting is still to be develop. Also ODR needs to be adjusted to the requirements of DaMaHub. But the basic ideas from ODR fit the open data part of DaMaHub.

Regarding the workflow I doubt that you can get all scientists to use a git-like workflow. Our idea is to provide a frontend that is as simple as dropbox but with a mercurial workflow in the backend (because git is a vicious beast of interdependent modules with poorly known internal restrictions and dependencies, while mercurial is a single-file python based well designed beauty that can do all git does but a lot nicer and consistent - end of rant) that is normally handled by the system but there in its full power if you want to use it.

#### Q: Re the self-describing data packages, I’m interested in the way you are writing metadata records to IPFS and blockchain, but I don't see how this would help to make the content retrieved by IPFS hash itself more interoperable and reusable etc (i.e. if retrieved out of context of the ODR).

A: We plan to enforce data packaging then at the moment you want to share your data with colleagues so you have an incentive to do it right at the start, and so when you want to open up the data most of the meta data is already there in a good quality.

