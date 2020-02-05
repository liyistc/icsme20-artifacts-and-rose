# ICSME'20 Joint Artifact Evaluation Track and ROSE Festival: Call for Submissions

The ICSME'20 Joint Artifact Evaluation Track and ROSE Festival is a 90-minute session of lightning talks of accepted reusable, available, replicated or reproduced artifacts, followed by a panel discussing issues of replication and reproducibility in software engineering. 
Our aim is to create a venue where researchers can receive public credit for facilitating and participating in open science in software engineering (specifically, in creating replicated and reproduced results). 
ROSE Festival is needed since most current conferences only evaluate research artifacts generated by that venue’s accepted papers. 
This makes it difficult for research papers to earn credit for replication and reproduction by other researchers (since no other team of researchers has yet to see this new result).


***Artifact Evaluation Track.*** Authors of **papers accepted to the ICSME 2020 Technical Track** are invited to submit artifacts associated with those papers to the ICSME Artifact Track for evaluation as a candidate **reusable, available** artifact.

***ROSE Festival.*** Authors of any prior SE work (published at ICSME, ICSE, FSE or ***elsewhere***) are invited to submit an artifact to the ICSME Artifact Track for evaluation as a candidate **replicated or reproduced** artifact. 

If the artifact is accepted:
- Authors will be invited to give lightning talks on this work at ICSME'20.
- We will work with the IEEE Xplore and ACM Portal administrator to add  badges to the electronic versions of the authors' paper(s), corresponding to the categories in the table below.
- The badges shown in the table below are the ACM badges, which particular badges to be used will be confirmed later, depending on ongoing discussions by the IEEE to introduce its own badges.

<table>
<thead></thead>
<tbody(s)>
<tr><td><strong>Functional</strong>	</td><td align="center"> <strong>Reusable</strong> </td><td align="center"> <strong>Available</strong></td><td align="center"> <strong>Replicated</strong> </td><td align="center"> <strong>Reproduced</strong> </td></tr>
<tr><td>No Badge </td><td align="center"> <dl><img src="https://2019.icse-conferences.org/getImage/orig/red.jpg" alt=""></dl>  </td><td align="center"> <dl><img src="https://2019.icse-conferences.org/getImage/orig/green.jpg" alt=""></dl>	   </td><td align="center">  <dl><img src="https://2019.icse-conferences.org/getImage/orig/blue.jpg" alt=""></dl> </td><td align="center">  <dl><img src="https://2019.icse-conferences.org/getImage/orig/deepBlue.jpg" alt=""></dl> </td></tr>
<tr><td> <!--Functional--> Artifacts documented, consistent, complete, exercisable, and include appropriate evidence of verification and validation </td><td align="center"> <!--Reusable--> Functional + very carefully documented and well-structured to the extent that reuse and repurposing is facilitated. In particular, norms and standards of the research community for artifacts of this type are strictly adhered to. </td><td align="center"> <!--Available-->  Functional + placed on a publicly accessible archival repository. A DOI or link to this repository along with a unique identifier for the object is provided. </td><td align="center"> <!--Replicated--> Available + main results of the paper have been obtained in a subsequent study by a person or team other than the authors, using, in part, artifacts provided by the author. </td><td align="center"> <!--Reproduced--> Available + the main results of the paper have been independently obtained in a subsequent study by a person or team other than the authors, without the use of author-supplied artifacts.</td></tr>
</tbody>
</table>


Papers with Artifacts of interest include (but are not limited to) the following:

- Software, which are implementations of systems or algorithms potentially useful in other studies.

- Data repositories, which are data (e.g., logging data, system traces, survey raw data) that can be used for multiple software engineering approaches.

- Frameworks, which are tools and services illustrating new approaches to software engineering that could be used by other researchers in different contexts.

This list is not exhaustive, so the authors are asked to email the chairs before submitting if their proposed artifact is not on this list.


## Evaluation Criteria

The ICSME artifact evaluation track uses a single-blind review process. Artifacts will be evaluated using the criteria in the last row of the above table.

Review will be via GitHub, the process for authors and reviewers is described [here](https://github.com/researchart/rose/blob/master/guidance.md). All submitting authors must supply a valid Github id that identifies themselves.

The goal of this track is to encourage reusable research products. Hence, no **functional** badges will be awarded. 

## Best Artifact Awards

There will be an ICSME 2020 Best Artifact Award to recognize the effort of authors creating and sharing outstanding research artifacts.

## Submission and Review

**IMPORTANT NOTE**: different categories have different submission procedures. See below.

Note that all submissions, reviewing, and notifications for this track will be via the GitHub repository [https://github.com/se-conf/icsme20-artifacts-and-rose](https://github.com/se-conf/icsme20-artifacts-and-rose).

- There will be no emails notifying authors, acknowledging a submission, or informing authors of the results of the review process.
- Instead, submitters can track the progress of their work by tracking its activity in the repo
- Submitting anything to this track will mean
	- Creating a GitHub account with your public name
	- Forking the master branch of our repo [https://github.com/se-conf/icsme20-artifacts-and-rose](https://github.com/se-conf/icsme20-artifacts-and-rose)
	- Creating a subdirectory one per submission, underneath one of the directories: 
		- https://github.com/se-conf/icsme20-artifacts-and-rose/submissions/reusable,
		- https://github.com/se-conf/icsme20-artifacts-and-rose/submissions/available,
		- https://github.com/se-conf/icsme20-artifacts-and-rose/submissions/replicated,
		- https://github.com/se-conf/icsme20-artifacts-and-rose/submissions/reproduced
	- Then adding submission file(s) to that directory
	- Then committing this branch.
	- Then submitting a pull request (back to master) *before the submission deadline*.
- All reviewing will be done in GitHub.
- Each submission will be processed in its own issue.
- Authors will be notified of final decisions when the track chairs add labels to the issue corresponding to the respective submission.


### Replicated and Reproduced Categories

For the “replicated” and “reproduced” categories, authors will need to offer appropriate documentation that their artifacts have reached that stage. For these categories, the submission process is to submit a one page (max) abstract in PDF via a GitHub pull request to [the submission repository](https://github.com/se-conf/icsme20-artifacts-and-rose/) (please check [here](https://github.com/researchart/rose/blob/master/guidance.md) for the structure of the repository). 

This abstract should contain the following information:

- TITLE: **A (Partial)? (Replication|Reproduction) of XYZ**. Please add the term **partial** to your title if only some of the original work could be replicated/reproduced.
- WHO: name the original authors (and paper) and the authors that performed the replication/reproduction.
  Include contact information (emails and **GitHub ids** (important)) for the authors. Please mark one author as the _corresponding author_.). Mark one author as the corresponding author.     
  **IMPORTANT**: include also a web link to a publically available URL directory containing (a)the original paper
  (that is being reproduced) and (b)any subsequent paper(s)/documents/reports that do the reproduction.     
  **IMPORTANT**: include also a web link to a publically avaialble URL directory containing (a)the original paper
  (that is being reproduced) and (b)any subsequent paper(s)/documents/reports that do the reproduction.
- WHAT: describe the "thing" being replicated/reproduced;
- WHY: clearly state why that "thing" is interesting/important;
- HOW: say how it was done first;
- WHERE: describe the replication/reproduction. If the replication/reproduction was only partial, then explain what parts could be achieved or had to be missed.
- DISCUSSION: What aspects of this "thing" made it easier/harder to replicate/reproduce. What are the lessons learned from this work that would enable more replication/reproduction in the future for other kinds of tasks or other kinds of research.

Two PC members will then review each abstract, possibly reaching out to the authors of the abstract or original paper. Abstracts will be ranked as follows.

- If PC members do not find sufficient substantive evidence for replication/reproduction, the abstract will be rejected.
- Any abstract that is judged to be unncessarily  critical of prior work will be rejected (\*).
- The remaining abstracts will be sorted according to (a) interestingness and (b) correctness.
- The top ranked abstracts will be invited to give lightning talks.

(\*) Our goal is to foster a positive environment that supports and
rewards researchers for conducting replications and reproductions. To
that end, we require that all abstracts and presentations pay due respect
to the work they are reproducing/replicating. Criticism of prior work
is acceptable only as part of a balanced and substantive discussion of
prior accomplishments.

For replicated and reproduced  badges, authors will be notified at the end of the reviewing process by the PC chairs.

### Reusable and Available Categories

This category is to be used by authors of the papers accepted to the Technical Track of ICSME'20. 

For these categories, authors submit by via fork and pull requests as described above, putting folders into the `submissions/reusable` or `submissions/available` folders, respectively. Authors must provide information showing how
reviewers can access and execute (if appropriate) their artifact.

Authors of the papers accepted to the Technical Track must perform the following steps to submit an artifact:

- Prepare the artifact
- Make the artifact available
- Document the artifact
- Submit the artifact

**1. PREPARING THE ARTIFACT**

There are two options depending on the nature of the artifacts: Installation Package or Simple Package. In both cases, the configuration and installation for the artifact should take less than 30 minutes. Otherwise the artifact is unlikely to be endorsed simply because the committee will not have sufficient time to evaluate it.

- _Installation Package_s:  If the artifact consists of a tool or software system, then the authors need to prepare an installation package so that the tool can be installed and run in the evaluator’s environment. Provide enough associated instruction, code, and data such that some CS person with a reasonable knowledge of scripting, build tools, etc. could install, build, and run the code. If the artifact contains or requires the use of a special tool or any other non-trivial piece of software the authors must provide a VirtualBox VM image or a Docker container image with a working environment containing the artifact and all the necessary tools.
Note that we expect that the artifacts will have been vetted on a clean machine before submission.

- _Simple Package_: If the artifact contains only documents that can be used with a simple text editor, a PDF viewer, or some other common tool (e.g., a spreadsheet program in its basic configuration) the authors can just save all documents in a single package file (zip or tar.gz).

**2. MAKING THE ARTIFACT AVAILABLE**

Authors need to make the packaged artifact (installation package or simple package) available so that the Evaluation Committee can access it. We suggest a link to a public repository or to a single archive file in a widely available archive format. If the authors are aiming for the categories “available” and beyond the artifact needs to publicly accessible. For larger files like VirtualBox images, we recommend the use of open repositories, a list of suitable providers can be found [here](https://www.nature.com/sdata/policies/repositories#general). In other cases, the artifacts do not necessarily have to be publicly accessible for the review process. In this case, the authors are asked to provide a private link or a password-protected link.

**3. DOCUMENTING THE ARTIFACT**

Authors need to write and submit  documentation explaining how to obtain the artifact package, how to unpack the artifact, how to get started, and how to use the artifacts in sufficient detail. The artifact submission must describe 
only the technicalities of the artifacts and uses of the artifact that are not already described in the paper. The submission should contain the following documents (in **markdown** plain text format within the submission root folder):

- A _CONTACT.md_ file listing emails and **GitHub ids** (important) for the authors. Please mark one author as the _corresponding author_.
- A _README.md_ main file describing what the artifact does and where it can be obtained (with hidden links and access password if necessary). Also, there should be a clear description of how to reproduce the results presented in the paper.
- A _STATUS.md_ file stating what kind of badge(s) the authors are applying for as well as the reasons why the authors believe that the artifact deserves that badge(s).
- A _LICENSE.md_ file describing the distribution rights. Note that to score "available" or higher, then that license needs to be some form of open source license.
- An _INSTALL.md_ file with installation instructions. These instructions should include notes illustrating a very basic usage example or a method to test the installation. This could be, for instance, information 
on what output to expect that confirms that the code is installed and working;  and that
the code is doing something interesting and useful.
- A copy of the accepted paper in pdf format.

**4. SUBMITTING AND REVIEWING THE ARTIFACT**  

For the reusable and available categories, the review process will be interactive as follows:

- ***Kick-the-tires:*** Before the actual evaluation, reviewers will check the integrity of the artifact and look for any possible setup problems that may prevent it from being properly evaluated (e.g., corrupted or missing files, VM won’t start, immediate crashes on the simplest example, etc.). 
The Evaluation Committee may contact the authors to request clarifications on the basic installation and start-up procedures or to resolve simple installation problems. 
Authors are required to provide response promptly to help reviewers resolve any technical issues with their artifact submission.

- ***Artifact assessment*** Reviewers evaluate the artifacts and provide comments on GitHub via anonymous GitHub ids. 

- ***Notification*** Authors are informed of the outcome.  

## REVIEW COMMITTEE
| | |
-------------------------:|:-------------------------
<img src="pc/maria-teresa.jpg" width="100">  | **[Maria Teresa Baldassarre](https://www.uniba.it/docenti/baldassarre-maria-teresa)** <br> The University of Bari, Italy |
<img src="pc/daniel-alenca.jpg" width="100"> | **[Daniel Alencar da Costa](https://www.otago.ac.nz/info-science/people/daniel-alencardacosta.html)** <br> The University of Otago, New Zealand |
<img src="pc/george-fourtounis.jpg" width="100"> | **[George Fourtounis](https://gfour.github.io/)** <br> University of Athens, Greece |
<img src="pc/raula.jpeg" width="100"> | **[Raula G. Kula](https://raux.github.io/)** <br> Nara Institute of Science and Technology, Japan |
![](pc/kamil-jezek.jpg) | **Kamil Jezek** <br> University of Sydney, Sydney |
<img src="pc/xuan-bach-le.jpg" width="100"> | **[Xuan-Bach D. Le](https://xuanbachle.github.io/)** <br> The University of Melbourne, Australia |
<img src="pc/sherlock-licorish.jpg" width="100"> | **[Sherlock Licorish](https://www.otago.ac.nz/info-science/people/sherlock-licorish.html)** <br> University of Otago, New Zealand|
<img src="pc/tosin-oyetoyan.jpg" width="100"> |**[Tosin Daniel Oyetoyan](https://www.hvl.no/en/employee/?user=6022952)** <br> Western Norway University of Applied Sciences, Norway|
<img src="pc/amjed-tahir.jpg" width="100"> | **[Amjed Tahir](https://www.massey.ac.nz/massey/expertise/profile.cfm?stref=481450)** <br> Massey University, New Zealand |
<img src="pc/lili-wei.jpg" width="100"> | **[Lili Wei](http://home.cse.ust.hk/~lweiae/)** <br> The Hong Kong University of Science and Technolog, Hong Kong |


## IMPORTANT DATES (all AOE)


- Friday 26 June 2020: Submission deadline (via pull request, see above)
- Saturday 26 June - Friday 3 July 2020: kick-the-tires  
- Sunday 19 July 2020 - Author notifications   
- Friday 7 August 2020 - Camera-ready submission
