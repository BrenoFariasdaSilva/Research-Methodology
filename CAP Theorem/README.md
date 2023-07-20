<div align="center">
  
# [Research-Methodology.](https://github.com/BrenoFariasdaSilva/Research-Methodology) <img src="https://github.com/BrenoFariasdaSilva/Research-Methodology/blob/main/assets/BooksStack.svg"  width="3%" height="3%">

</div>

<div align="center">
  
---

My Work Proposal for the Research Methodology Subject that i did my university course at [UTFPR-CM](https://pt.wikipedia.org/wiki/Universidade_Tecnol%C3%B3gica_Federal_do_Paran%C3%A1).
  
---

</div>

<div align="center">

![wakatime](https://wakatime.com/badge/github/BrenoFariasdaSilva/Research-Methodology.svg)
  
</div>

<div align="center">
  
![RepoBeats Statistics](https://repobeats.axiom.co/api/embed/1a121081a586a21625ff4e058ff4edf59269e1a9.svg "Repobeats analytics image")

</div>

<div align="center">

# [CAP Theorem in Distributed Systems: A Systematic Review of Principles.](https://github.com/BrenoFariasdaSilva/Research-Methodology/blob/main/CAP%20Theorem/Research%20Methodology%20-%20Work%20Proposal%20-%20CAP%20Theorem%20-%20TCC%20Model%20UTFPR%20V2.5A.pdf)

</div>

## Table of Contents
- [Research-Methodology. ](#research-methodology-)
- [CAP Theorem in Distributed Systems: A Systematic Review of Principles.](#cap-theorem-in-distributed-systems-a-systematic-review-of-principles)
	- [Table of Contents](#table-of-contents)
	- [Abstract](#abstract)
	- [Literature Review](#literature-review)
		- [Theoretical Foundation](#theoretical-foundation)
		- [Related Works](#related-works)
	- [Work Proposal](#work-proposal)
		- [Proposal](#proposal)
		- [Methodology](#methodology)
		- [Expected Results and Contributions](#expected-results-and-contributions)


## Abstract
This paper proposes a systematic review of the CAP theorem in distributed systems, offering an updated view of recent advances and future trends related to CAP.

The methodology adopted in this work consists of a literature review of the CAP and its principles. Primarily, scientific articles will be researched, but books, conferences, and online resources will also be considered options, selecting those directly addressing CAP and its applications or misconceptions in distributed systems. Since the focus is on using articles, we will search for them in major repositories, such as ACM Digital Library, IEEE Xplore, Google Scholar, and SpringerLink. We aim to find at least 30 viable articles, but preliminary analysis of their methods and results will be conducted to narrow down to the top 10 candidates. From the analysis of these materials, the main published results in the area will be extracted, providing a comprehensive and updated view of the state-of-the-art.

This work aims to offer a comprehensive overview of the main published results in the field of CAP in distributed systems. It will present different consistency models, most used data replication techniques, and consensus algorithms.

## Literature Review
A literature review is necessary, as it will present the basic and fundamental concepts for an overview of the research area and the problem. The related work subsection will list relevant proposals, which will be compared with the present work.

### Theoretical Foundation
The CAP Theorem was proposed by Eric Brewer and is well-defined in the article "Brewer’s CAP Theorem" (SALOMÉ, 2012), which states, "The CAP theorem states: You can have at most two of these properties for any shared-data system." In other words, the theorem describes that in a distributed system, it is impossible to simultaneously guarantee consistency, availability, and partition tolerance. These three attributes are well-defined in the article "Perspectives on the CAP Theorem" (GILBERT; LYNCH, 2012).

The first term of the CAP acronym, "consistency," refers to the uniformity of data in a distributed system. A system is considered consistent when all replicas of the data on different nodes present the same version of the data at a given time. The second term of the acronym deals with "availability," which refers to a system's ability to respond to requests even in the face of failures or network partitions. A system is considered available if users can access and receive responses, even if some nodes or connections fail. Finally, the last letter referring to the theorem deals with "partition tolerance," which concerns a system's ability to continue operating and ensuring consistency and availability even if network partitions occur. Understanding these concepts is essential to comprehend the challenges and solutions related to the CAP Theorem in distributed systems.

These definitions are well-explained in the literature and are mentioned in various studies, such as in the articles "Brewer’s CAP Theorem" (SALOMÉ, 2012) and the blog post "You Can’t Sacrifice Partition Tolerance" (HALE, 2010), where the author cites the work of Seth Gilbert and Nancy Lynch in the article "Perspectives on the CAP Theorem."

### Related Works
Note: Compare all with my work!

- "Perspectives on the CAP Theorem" (GILBERT; LYNCH, 2012): This work offers a comprehensive analysis of different perspectives and interpretations of the CAP Theorem. It explores the theoretical and practical implications of the Theorem and discusses the necessary trade-offs for contexts prioritizing consistency or availability in distributed systems. Additionally, it includes a relevant chapter demonstrating how to achieve both consistency and availability through data segmentation, user operations, among others. Moreover, the authors of this article are responsible for the formal proof of CAP in the article "Brewer’s Conjecture and the Feasibility of Consistent Available Partition-Tolerant Web Services" (GILBERT; LYNCH, 2002).

- "You Can’t Sacrifice Partition Tolerance" (HALE, 2010): This blog post emphasizes the importance of partition tolerance in the context of the CAP Theorem. It argues that partition tolerance is a fundamental requirement for resilient distributed systems and explores the implications of this choice, such as in real systems, it is impossible to handle trillions of simultaneous requests with a centralized architecture that is not partitioned in the network (an argument also presented in "Eventually Consistent" (VOGELS, 2009)). Additionally, the author of the CAP Theorem used this blog post as motivation to write the article below due to the misconceptions around CAP.

- "Brewer’s CAP Theorem" (SALOMÉ, 2012): In this work, the author presents the CAP Theorem, mentioning the three properties (consistency, availability, and partition tolerance) defined by other authors and their mutual relationship. The article provides an overview of the Theorem and its practical implications, mentioning the formulation by Eric Brewer in the article "CAP Twelve Years Later - How the 'Rules' Have Changed," that the decision is not binary. Finally, the author also mentions (GILBERT; LYNCH, 2002) along with real-world application examples like Amazon Dynamo.

- "CAP Twelve Years Later - How the 'Rules' Have Changed" (BREWER, 2012): This work revisits the CAP Theorem after twelve years of its initial formulation. It discusses how misconceptions of CAP have evolved and how distributed systems' technologies and practices have adapted over time.

In comparison with these related works, the proposed article "CAP Theorem in Distributed Systems: A Systematic Review of Principles" aims to fill the gap in understanding and dissemination of the CAP Theorem, offering a systematic review of the literature on the topic. It focuses on providing a comprehensive overview, identifying research gaps, and presenting practical recommendations for applying the CAP Theorem in distributed systems.

## Work Proposal
In the development section of this article, we will explore the proposal of this study, along with a better description of the method, an explanation of the expected results, and finally, the execution schedule of this study.

### Proposal
The main objective of this work is to conduct a systematic review of the literature on the CAP Theorem in distributed systems, to provide an in-depth understanding of the underlying principles, trade-offs, and strategies to address consistency and availability challenges, to introduce new researchers to the field. The specific objectives are:
- Present an overview of the CAP Theorem, including its definitions and implications for distributed systems.
- Conduct a comprehensive literature review, seeking relevant scientific articles, books, conferences, and online resources that address the CAP Theorem and related aspects.
- Analyze and compare the found works, identifying the main approaches and proposed solutions to address the CAP Theorem trade-offs.
- Investigate case studies and practical implementation experiences of distributed systems to enrich the understanding of challenges and solutions associated with the CAP Theorem.
- Identify gaps in the literature and highlight possible areas of future research related to the CAP Theorem in distributed systems.

### Methodology
The methodology adopted for the development of this work will be based on a systematic literature review. The steps to be followed are:
1. Definition of search criteria: clear search criteria will be established, including keywords and filters to select relevant articles for review.
2. Selection of articles: articles will be selected based on pre-defined inclusion and exclusion criteria, considering their relevance to the study topic.
3. Analysis of articles: selected articles will be analyzed in detail, identifying key concepts, approaches, trade-offs, and presented results.
4. Synthesis of results: the results will be synthesized into a systematic review, organizing the main points discussed in the articles and identifying gaps in the literature.

### Expected Results and Contributions
It is expected that this work will provide a comprehensive view of the principles of the CAP Theorem in distributed systems, highlighting the trade-offs and challenges associated with consistency and availability. Additionally, it is expected to identify solutions and approaches proposed in the literature to address the CAP Theorem trade-offs. The main contributions of this work are:
- Systematic literature review of the CAP Theorem in distributed systems.
- Comparative analysis of approaches and solutions found in the literature.
- Identification of gaps in current research and suggestion of possible areas for future research.
- Provision of a reference article for professionals and researchers interested in the topic.

This schedule has a total duration of 24 weeks, considering an average dedication of 10 hours per week.
