
# Ethereum OASIS Project Governance

This document defines the Ethereum OASIS Open Project's community governance per [OASIS Open Projects Governance Policy](https://github.com/oasis-open-projects/documentation/blob/master/policy/project-governance.md).

# Our Goal
Our primary goal is to increase the minimum quality of Ethereum-related standards.  We aim for the mean quality of standards that pass through our process to be greater than the mean quality that have not.
<!--- Do you want to say something about what you mean by 'quality'? For example, does quality mean that the spec has fewer places where developers make conflicting but equally valid interpretations of the spec? Or maybe that developers have to ask fewer questions to understand it? Or that developers can implement successfully interoperating implementations with few places where they have to meet to agree on more efficiently?  --->

## Overview

The **Ethereum OASIS Open Project** community is governed by this document and in accordance with [OASIS Open Project Rules](../board-docs/open-projects-rules.md). The purpose of this document is to define how community should work together to achieve its technical goals.
<!--- I suggest you add something like "Aspects of the work of the community may also be covered by the rules of the [OASIS Committee Operations Process](https://www.oasis-open.org/policies-guidelines/oasis-committee-operations-process-2018-05-22) and other [OASIS policies](https://www.oasis-open.org/policies-guidelines). --->

The Ethereum OASIS Open Project aims to work by lazy consensus within each TSC, as described under [Decision Making](#decision-making) below.  Each TSC is responsible for determining when it has lazy consensus. 

Within a TSC, those who show up and do the work get to make the decisions.
<!--- This is an excellent aspirational statement. You may want to make clear what 'show up and do the work' means in practice to avoid misunderstandings. For example, has someone who read all the emails, reviewed pull requests, read all documents, attended any calls, etc. but never had anything to say 'done the work?' Does a person have to make pull requests? ---> 

The TSC should be open to changing decisions based on new information, if a consensus emerges to make such a change.
<!--- I suggest taking this out. It will happen naturally, without being listed in the procedure, and having this statement could possibly be seen as an invitation for one party to reargue decisions that they don't like. "Oh, but y'all didn't consider this..." ---> 

## Code Repositories

The following code repositories are governed by the **Ethereum OASIS Open Project** community and maintained under the project namespace:

* **[Ethereum OASIS Project repository](https://github.com/ethereum-oasis/oasis-open-project):** The main repository.
* **[baseline](https://github.com/ethereum-oasis/baseline)**
* **[baseline-website](https://github.com/ethereum-oasis/baseline-website)**

## Community Roles

All members of the community must complete and abide by the
the [Required Legal Agreements](#Required-Legal-Agreements), which includes abiding by the [OASIS Open Projects Code of Conduct](https://github.com/oasis-open-projects/documentation/blob/master/CODE_OF_CONDUCT.md). Failure to meet these requirements means a contributor is no longer eligible to participate. <!--- how about this instead: "Violation of these rules may result in a person being barred from further participating." ---> 

* *Contributor*: People who have contributed to a TSC repository in the last 2 years. Anyone can be a contributor, so long as they agree to contribute under the terms of this document.
* *Technical Steering Committee (TSC) chair*: one or more persons appointed by the Project Governing Board to ensure the TSC runs smoothly. The chair is empowered to suspend a contributor temporarily or permanently (for example for egregiously or repeatedly breaching the Code of Conduct). Appeals can be sent to the PGB under the same 2/3 majority rule used for overturning consensus decisions.
<!--- I suggest splitting this into 2 parts: 
* *Technical Steering Committee (TSC) member*: persons appointed by the PGB to manage and drive the day-to-day technical work of the project.
* *Technical Steering Committee (TSC) chair*: one or two members of the TSC appointed by the Project Governing Board to manage the agenda for the group, schedule and run any meetings, and generally ensure the TSC runs smoothly. The chair is empowered to suspend a contributor temporarily or permanently (for example for egregiously or repeatedly breaching the Code of Conduct). Appeals can be sent to the PGB under the same 2/3 majority rule used for overturning consensus decisions. 
--->
* *Project Governing Board (PGB)*: The Project Governing Board is charged with ensuring the overall project runs smoothly, as described below. <!--- The PGB, in consultation with the TSC, also has final approval over releases and decisions to advance work to the OASIS standardization process. ---> 


## Project Leadership

Each **Technical Steering Committee** (**TSC**) has a chair (or co-chairs) appointed (or removed) by the PGB. The chair of a TSC is responsible in the first instance for the day-to-day functioning of the TSC.  The chair of each TSC should have a firm understanding of the technology under the TSC's purview, and the [skills of a Technical Project Manager](https://www.jobhero.com/technical-program-manager-job-description/).

### Project Governance Board
The **Project Governance Board** (**PGB**)'s responsibility is to ensure that every TSC is running reasonably well. With a [special majority](#Special-Majority-Vote), the PGB can

  * overturn or confirm a TSC's declared consensus;
  * replace a TSC chair;
  * determine that a participant has failed to abide by the Code of Conduct, and declare them ineligible to participate for a term the PGB decides;
  * create or close TSCs;
  * appoint its own chair;
  * change this governance document.

The **PGB** also follows and is responsible for upholding the [OASIS Open Projects Rules](https://github.com/oasis-open-projects/documentation/blob/master/board-docs/open-projects-rules.md).

<!--- If membership in the PGB exceeds <threshold #, e.g. 12> members, then the PGB may establish an ad-hoc steering committee composed of each TSC representative seated on the PGB and two or three Sponsor representatives of the PGB. The purpose of the ad-hoc steering committee will be to help the full PGB function effectively and may include such tasks as proposing priorities for issues, recommending solutions for issues under consideration by the PGB, and organizing agenda items for consideration at full PGB meetings. Final discussion and decision-making will remain with the full PGB. --->

### PGB Membership

The PGB is comprised of one representative from each Sponsoring organization. Additionally, each TSC Chair is a member of the PGB. The PGB roster is maintained at https://github.com/ethereum-oasis/oasis-open-project#governance

### Becoming an Editor

Editors are appointed (or removed) by the relevant TSC chair(s). Any Contributor is eligible to be an Editor.

Editors are expected to be actively involved in discussion of Proposals and helping them reach the quality level required to reach Candidate stage, and more generally to actively maintain the overall quality of their TSC's specification(s).

As defined in [Decision Making](#Decision-Making), Editors are empowered to interpret the "Lazy Consensus" of a TSC, subject to direction from the chairs to implement a formally declared decision.

## Starting and maintaining a TSC

### Initial requirements

To start a new TSC, there must be
* a request from at least three sponsoring organizations who commit to participating
* a named Chair and Vice Chair who have agreed to the expectations for chairs

Although it is not required, ideally a proposed TSC will have at least 5 initial participants.

### Maintenance requirements

To be considered _active_, a TSC must satisfy the following heartbeat requirements:
* at least 3 active participants representing at least 2 different companies
* at least 1 commit per month in one repo

Any TSC failing to meet one or more of the above heartbeat requirements is considered _inactive_.

Note that the PGB may permit the formation or continuation of a TSC that does not meet the above requirements.

### TSC funding

The Ethereum OASIS Open Project supports all of its TSCs.  However, if a TSC would like additional resources, beyond those provided by default by OASIS, to support its initiatives, it may seek additional funding.
* Only Ethereum Open Project Sponsors may do this.  Any Sponsor may provide additional funding through OASIS that is designated for a specific TSC to allocate.
* No advance vote or approval by the PGB is required.
* The TSC determines where to direct the funds collected, either directly or via a process they establish.
* The TSC and its projects may not use the OASIS or Ethereum Open Project names when seeking or using additional funding unless the PGB has been notified in advance.  
* The TSC must give advance notice to the PGB before disbursement of any funds.
* The PGB may veto the acquisition or use of such funding at any time for any reason; the intent is to ensure that the acquisition and use of any such funding is consistent with the overall goals of the Ethereum Open Project.

If a TSC chooses to seek funding outside of the OASIS funding path, they still must not use the OASIS, Ethereum Open Project, or TSC project names when seeking or using additional funding unless the PGB has been notified in advance.

## Closing a TSC

The Project Governing Board may close a TSC at any time.

An *active* TSC may only be closed with a Special Majority Vote of the PGB.

Any TSC which is *inactive* may be closed with a Full Majority Vote.

A TSC which has been *inactive* for at least 6 consecutive months may be closed with a Simple Majority Vote.

Note that closing a TSC ends any conference calls and specification editing privileges but will not automatically remove any materials.  <!--- This may conflict with the Open Project rules. I'll have to check. I believe the rules say that we'll remove branding and other identifiers but the project will remain 'live.'" --->

## Decision Making

Everyday TSC decisions will be reached by [lazy consensus](https://communitymgt.fandom.com/wiki/Lazy_consensus). Editors are empowered to implement the consensus of a TSC as they see it. The TSC chair is empowered to direct the Editor(s) to make a change reflecting a decision of the TSC.

If the chairs of a TSC determine that consensus is not possible, then the TSC will not publish any output. 

Any TSC lazy consensus decision can be overturned by a $\geq 2/3$ majority of the PGB at the request of a TSC contributor.

The PGB is unlikely to overturn a decision based on a single objection from a contributor who has barely participated, or an apparent "[branch-stacking](	)" (aka Room Packing) exercise. 

Lazy consensus does _not_ apply to certain decisions of the **PGB**, as defined elsewhere in this document.

### Lazy Consensus

Out of respect for other contributors, major changes should also be accompanied by a post on an email list or bulletin board (i.e., the OASIS-provided mailing list for each TSC) as appropriate. Author(s) of proposal, Pull Requests, issues, etc. will give a time period of no less than seven (7) working days for comment and remain cognizant of popular observed world holidays.

Other maintainers may chime in and request additional time for review, but should remain cognizant of blocking progress and abstain from delaying progress unless absolutely needed. The expectation is that blocking progress is accompanied by a guarantee to review and respond to the relevant action(s) (proposals, PRs, issues, etc.) in short order.

Lazy Consensus is practiced for all projects in our org, including the main project repository, community-driven sub-projects, and the community repo that includes proposals and governing documents.

Lazy consensus does _not_ apply to some PGB decisions identified elsewhere in this document, such as:
* Appointing or Removing TSC chairs or PGB Members
* Removing TSC Members, other than for failure to abide by the formal legal obligations described below
* Moving a specification to the OASIS standards track

### Special Majority Vote

A Special Majority Vote is a vote in which at least 2/3 (two thirds) of the eligible voters vote "yes" and no more than 1/4 (one fourth) of the eligible voters vote "no". These numbers are based on the total number of eligible voters in the committee. Abstentions are not counted. For example, in a Committee in which there are 30 Voting Members, at least 20 Voting Members must vote "yes" for a motion to pass; but if 8 or more vote "no" then the motion fails.

<!--- Special Majority Votes must be run by the OASIS OP Administrator. ---> 

Certain issues require a Special Majority Vote of the PGB, such as appointing TSC chairs or changing this governance document.

## Proposal Process
Large changes, including new features, should be preceded by a proposal. This process allows for all members of the community to weigh in on the concept (including the technical details), share their comments, ideas, and use cases, and offer to help. It also ensures that members are not duplicating work or inadvertently stepping on toes by making large conflicting changes.

The TSC's project roadmap is defined by accepted proposals. Each TSC accepts and develops proposals in a process patterned after the five development stages in the [TC39 process document](https://tc39.es/process-document/):
* Strawman (a description of an idea)
* Proposal (a formal request that it be considered for inclusion)
* Draft (a "specification-shaped" version of the proposal to be considered for implementation)
* Candidate (a "standard-ready" version for implementation testing before formal adoption)
* FInished (stable, in the formally published release version)

TSCs may tweak the process, and if they do so must record TSC-specific processes in a "Contributing.md" file in their project's main repository.

Each proposal should be developed in a separate GitHub repository, which is then merged into the main repository once it has been accepted into the canonical specification.

#### Creating a new proposal
To make a feature request, document the problem and a sketch of the solution with others in the community and TSC.  One place to do this is in the respective OASIS TSC mailing list or Discourse.

Your goal will be to convince others that your suggestion is a useful addition and recruit TSC members to help turn your request into a Proposal and shepherd it to Finished.

## Required Legal Agreements
Contributors to any TSC project must abide by the [OASIS Open Projects IPR Policy](https://github.com/oasis-open-projects/documentation/blob/master/policy/clas-and-special-covenant.md) and Apache 2.0 License agreement as outlined in the license.md file. 

All contributors are required to make these rights available by signing a [Contributor License Agreement (CLA)](https://github.com/oasis-open-projects/documentation/blob/master/templates/individual-cla.md) and patent non-assert for non-trivial contributions releasing all contributions under Apache2. If you have questions about these policies, please contact the [OASIS Open Project Administrator](op-admin@oasis-open.org). 

All participants must also abide by the terms of the [OASIS Open Projects Code of Conduct](https://github.com/oasis-open-projects/documentation/blob/master/CODE_OF_CONDUCT.md).

### Proposal Lifecycle

Each TSC will probably create their own lifecycle.  But as a possible default, each proposal can be marked with different status labels to represent the status of the proposal:

* **New**: Proposal is just created.
* **Reviewing**: Proposal is under review and discussion.
* **Accepted**: Proposal is reviewed and accepted (either by consensus or vote).
* **Rejected**: Proposal is reviewed and rejected (either by consensus or vote).

## Required conditions for acceptable complete specifications

Each TSC specification will only be considered complete when:

* It has appropriate documentation <!--- created using the Open Project specification template supplied by the OP Administrator. --->
* It has a test suite for all normative statements in the specification

Examples of acceptable documentation: 
* [The MDN JavaScript specs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON/parse)
* W3C's [Generic Sensor API](https://www.w3.org/TR/generic-sensor/)
* [The Jello Paper](https://jellopaper.org)

Examples of insufficient documentation:
* [The Yellow Paper](https://gavwood.com/paper.pdf)

## Updating Governance

Substantive changes to this document may be made by a Special Majority Vote of the PGB.
