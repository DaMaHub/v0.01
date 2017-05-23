# Data Management Hub

## Introduction

We are living through a fundamental change, progressing from an era in which data was scarce and hard to access to an era in which data exceeds our ability to extract meaning from it. 

Data fusion from different fields of science and across institutions is gaining importance in making new discoveries and replicating old ones [1]. 

Computer science is now called to action to develop new infrastructures which will make it possible to employ data exploration, analysis and mining techniques to extract insight from large datasets with the help of artificial intelligence [2]. Such infrastructures must be resilient, permanent and linked (read ‘useful’).

The explosion of data-intensive research is challenging researchers, publishers and librarians to create new solutions to link publications to research data (and vice versa), to facilitate data mining and to manage the dataset as a potential unit of publication.

The emerging research area of digital biomarkers combine the aforementioned challenges as the aggregation and analysis of data is an integral part of the research.

This business case utilizes a workflow approach to academic research and aims to develop an integrated scholarly communication infrastructure which efficiently combined article and data publishing in the field of digital biomarkers research.

## Mandatory Data Management Requirements

Funders of academic research in Europe consistently emphasized the importance of research data being made available in addition to original research articles as a means of comprehensive and sustainable reporting of research findings. As a result, it is mandatory to have a data management plan in place for research grants issued under the FP7 framework agreement and advise grantees that “5% of total research expenditure should be spent on properly managing and 'stewarding' data in an integrated fashion.” [11]

With regard to clinical research in particular, there is growing consensus among key organisation about the societal relevance of shared research data: “The International Committee of Medical Journal Editors (ICMJE) believes that there is an ethical obligation to share data generated by interventional clinical trials responsibly because participants have put themselves at risk.” [10]

##  Data Management Hub

The Data Management Hub is a distributed data management platform which fits into researchers’ workflows, enables secure collaboration on sensitive data [4] and empowers dissemination of research outcomes so that data will remain useful for decades [5]. The Data Management Hub will link research data and publications permanently to each other. 

Peer reviewing publication and re-use of open research data will be delivered by this platform. Careerwise, by using the Data Management Hub, researchers will benefit from unambiguous data authorship attribution. 

The Data Management Hub platform authenticates and timestamps generated research data automatically, and enables scientists to benefit from a state-of-the art version management system in order to empower replications of scientific studies universally.

##  Technologies

The Data Management Hub uses a hybrid topology, based on a distributed network of servers in the cloud and at universities.  The platform is built upon two innovative openly licensed technologies: 

* the blockchain -  an immutable digital public ledger that is distributed, verified and monitored by multiple sources at the same time [6], and 

* the Interplanetary File System (IPFS) - a distributed peer-to-peer hypermedia protocol [7]. 

Publications and underlying research data are stored on IPFS that also connects all nodes. Each publication is addressed by unique immutable cryptographic hash (permanent URL / persistent identifier).

Permissioned blockchains are immutable records of transaction history performed by a predefined list of subjects with known identities. Due to its distributed nature, blockchains provide a built-in means of recovery from database corruption and a mechanism for definitive data verification. 

## Data Security and Privacy

The Data Management Hub can be seen as two module solution: a secure work space and an open data repository:

* The secure workspace enables researchers to collaborate on sensitive data by authentication only.
 
* The open data repository is where scientists publish their data, interact with others and share research outcomes. [4]

The architecturally distributed network of nodes will take care of open data publishing, archiving and interaction with data on a worldwide scale.  Each file submitted to the network is given a unique cryptographic hash (a persistent identifier) that allows the IPFS network to automatically delete duplicates and track version history for every file. Historic versioning prevents information from being easily erased. Since the files are provided by distributed nodes, download speeds are higher. [8]

## Objectives

The data management hub is ideally positioned to support clinical researchers along the different steps of the research workflow. Our goal is to map out the specific data management needs and requirements for the digital biomarkers community and subsequently provide a tailored software solution which integrates with the specific research practices and publication routines. 

### Summary

The Data Management Hub allows researchers to manage research data in a seamless process from experimentation to publication. The Data Management Hub integrates enabling scientists 

to keep sensitive data secure and,
to collaborate between research groups,  
to make research data accessible, interoperable and reusable,
to effortlessly publish data together with original journal articles.
 
The research data infrastructure enabled with the Data Management Hub will be permanent, persistent and linked and will have a transformative potential for the way we do science in the future.


## References


[^1]: “The STM Report: An overview of scientific and scholarly journal publishing.” Mark Ware and Michael Mabe. (2015) [http://www.stm-assoc.org/2015_02_20_STM_Report_2015.pdf](http://www.stm-assoc.org/2015_02_20_STM_Report_2015.pdf) [cited 7 May 2017] 

[^2]: "Computer-Aided Discovery Tools for Volcano Deformation Studies with InSAR and GPS." Victor Pankratius et al. (2016) [https://agu.confex.com/agu/fm16/meetingapp.cgi/Paper/139594](https://agu.confex.com/agu/fm16/meetingapp.cgi/Paper/139594) [cited 7 May 2017]

[^3]: “A Journal is a Club: A New Economic Model for Scholarly Publishing.” Potts, Jason, John Hartley, Lucy Montgomery, Cameron Neylon, and Ellie Rennie. (2016) (Available at SSRN: [http://ssrn.com/abstract=2763975](http://ssrn.com/abstract=2763975) [cited 20 April 2016]

[^4]: "Study on the EC Open Research: Data Pilot and Personal Data Rules." OpenAIRE. (2017) [https://www.openaire.eu/public-documents?id=864&task=document.viewdoc](https://www.openaire.eu/public-documents?id=864&task=document.viewdoc) [cited 20 April 2016]

[^5]: "ODR: Scholarly Publishing & Knowledge Preservation." Kubrik Engineering. (2017) [http://kubrik.io/projects/odr/](http://kubrik.io/projects/odr/) [cited 7 May 2017]

[^6]: “All you need to know about blockchain, explained simply.” Rosamond Hutt. (2017). 
[https://www.weforum.org/agenda/2016/06/blockchain-explained-simply/](https://www.weforum.org/agenda/2016/06/blockchain-explained-simply/) [cited 5 May 2017]

[^7]: IPFS [https://ipfs.io](https://ipfs.io) [cited 7 May 2017]

[^8]: "The IPFS and the blockchain" [https://www.deepdotweb.com/2017/05/09/the-ipfs-and-the-blockchain/](https://www.deepdotweb.com/2017/05/09/the-ipfs-and-the-blockchain/) [cited 9 May 2017]

[^9]: Since July 2016 every application under Horizon 2020 program must include Data Management Plan - "H2020 Program Guidelines on Open Access to Scientific Publications and Research Data in Horizon 2020", Version 3.1., 25. page 8, August 2016 [https://ec.europa.eu/research/participants/data/ref/h2020/grants_manual/hi/oa_pilot/h2020-hi-oa-pilot-guide_en.pdf ](https://ec.europa.eu/research/participants/data/ref/h2020/grants_manual/hi/oa_pilot/h2020-hi-oa-pilot-guide_en.pdf)[cited 23 January 2017]

[^10]: "Sharing Clinical Trial Data — A Proposal from the International Committee of Medical Journal Editors." Darren B. Taichman et al. (2016) [http://www.nejm.org/doi/10.1056/NEJMe1515172](http://www.nejm.org/doi/10.1056/NEJMe1515172) [cited 7 May 2017]

[^11]: "Realising the European Open Science Cloud." European Union. (2016) [https://ec.europa.eu/research/openscience/pdf/realising_the_european_open_science_cloud_2016.pdf#view=fit&pagemode=none](https://ec.europa.eu/research/openscience/pdf/realising_the_european_open_science_cloud_2016.pdf#view=fit&pagemode=none) [cited 7 May 2017]

[^12]: "Guidelines on FAIR Data Management in Horizon 2020." European Union. (2016) [https://ec.europa.eu/research/participants/data/ref/h2020/grants_manual/hi/oa_pilot/h2020-hi-oa-data-mgt_en.pdf](https://ec.europa.eu/research/participants/data/ref/h2020/grants_manual/hi/oa_pilot/h2020-hi-oa-data-mgt_en.pdf) [cited 7 May 2017]
