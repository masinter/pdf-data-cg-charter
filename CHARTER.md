# [DRAFT] PDF and Open Data Community Group Charter

{TBD: remove next sentence before submitting for approval} This Charter is work in progress. To submit feedback, please use https://github.com/masinter/pdf-data-cg-charter   Issues where Charter is being developed.

*   This Charter: {TBD: URI for github masinter/pdf-data-cg-charter}
*   Previous Charters in Git history
*   Start Date: July 2016

{{include Last Modifed when posting}}

## Goals

The PDF and Open Data Community Group will work to define methods of storing and retrieving (linked open) data to and from PDF files, elevating the PDF format from a "one-star" to "five-star" [open data format](http://5stardata.info/en/). Much of the world's data is already stored in PDFs, but the format's limited innate data retrieval capabilities hold back open data as a whole. Deliverables and specifications produced by this group will help overcome this limitation.

Complete tooling for open data in PDFs should be able to extract and act upon the following objects:

* Images, including captions.
* Data tables (see [CSV on the Web WG](https://www.w3.org/2013/csvw/wiki/Main_Page)).
* Document text, including markup.
* Tables of contents and indices for the document.
* Annotations (see [Annotations WG](https://www.w3.org/annotation/)).
* Citations (see [Force 11 guidelines](https://www.force11.org/group/joint-declaration-data-citation-principles-final)).
* Typed objects within the document, using RDFa and Schema.org to disambiguate and help machines understand document content.

## Scope of Work

The Community Group will produce specifications and tooling targeted at producers and consumers of data, with the intention of standardizing the storage of linked open data within PDFs, without making the job of the publisher more difficult. This means that any method used to store data must be simple and versatile enough not to require modification of the data before storage, while still being easy for users to extract and interpret. Additionally, test cases should demonstrate a broad range of uses, mirroring the broad range of applications for data PDFs in the real world. Tooling needs to be adapted to cover the majority of cases out of the box.

Useful tools for open data include: {{need to add more info here!}}

* resolve technical questions
* XMP vs. attached files
* advanced capabilities
* consider other file formats which might also benefit
* give feedback to ISO 32000 committee about requirements

{Include enough to cover any possible technical areas that patent policy might apply to.  }

### Out of Scope

Two major elements are out of the scope of this group:

* Reinventing the OCR wheel. OCR for PDF already exists, built into Adobe Acrobat, and that capability can be leveraged to extract data if needed. Designing custom automatic data extraction and text recognition for open data is outside of this group's scope.
* Prescribing any specific implementation of open data in PDFs. While this group seeks to build standards and test cases, it does not seek to push any particular implementation on producers or users.

## Deliverables

### Specifications

We imagine producing a document:

* Guidelines for Linked Open Data and PDF


{TBD: Provide a brief description of each specification the group plans to produce. Where an estimate is possible, it can be useful to provide an estimated schedule for key deliverables. As described below, the group may later modify the charter deliverables. if no specifications, include: "No Specifications will be produced under the current charter."}

### Non-Normative Reports

(not sure which parts are normative)

The group may produce other Community Group Reports within the scope of this charter but that are not Specifications, for instance use cases, requirements, or white papers.

### Test Suites and Other Software

examples
a test suite

{TBD: If there are no plans to create a test suite or other software, please state that and remove the following paragraph. If Github is not being used, then indicate where the license information is. If GitHub is being used link to your LICENSE.md file in the next paragraph.}

The group MAY produce test suites to support the Specifications. Please see the GitHub LICENSE file for test suite contribution licensing information.

## Dependencies or Liaisons

{TBD: List any significant dependencies on other groups (inside or outside W3C) or materials. }
Liaison with ISO PDF community


## Community and Business Group Process

The group operates under the [Community and Business Group Process](https://www.w3.org/community/about/agreements/). Terms in this Charter that conflict with those of the Community and Business Group Process are void.

As with other Community Groups, W3C seeks organizational licensing commitments under the [W3C Community Contributor License Agreement (CLA)](http://www.w3.org/community/about/agreements/cla/). When people request to participate without representing their organization's legal interests, W3C will in general approve those requests for this group with the following understanding: W3C will seek and expect an organizational commitment under the CLA starting with the individual's first request to make a contribution to a group [Deliverable](#deliverables). The section on [Contribution Mechanics](#contrib) describes how W3C expects to monitor these contribution requests.

## Work Limited to Charter Scope

The group will not publish Specifications on topics other than those listed under [Specifications](#specifications) above. See below for [how to modify the charter](#charter-change).

## Contribution Mechanics

Substantive Contributions to Specifications can only be made by Community Group Participants who have agreed to the [W3C Community Contributor License Agreement (CLA)](http://www.w3.org/community/about/agreements/cla/).

Specifications created in the Community Group must use the [W3C Software and Document License](http://www.w3.org/Consortium/Legal/2015/copyright-software-and-document). All other documents produced by the group should use that License where possible.

{TBD: if CG doesn't use GitHub replace the remaining paragraphs in this section with: "All Contributions are made on the groups public mail list or public contrib list"}

Community Group participants agree to make all contributions in the GitHub repo the group is using for the particular document. This may be in the form of a pull request (preferred), by raising an issue, or by adding a comment to an existing issue.

All Github repositories attached to the Community Group must contain a copy of the [CONTRIBUTING](https://github.com/w3c/licenses/blob/master/CG-CONTRIBUTING.md) and [LICENSE](https://github.com/w3c/licenses/blob/master/CG-LICENSE.md) files.

## Transparency

The group will conduct all of its technical work in public. If the group uses GitHub, all technical work will occur in its GitHub repositories (and not in mailing list discussions). This is to ensure contributions can be tracked through a software tool.

Meetings may be restricted to Community Group participants, but a public summary or minutes must be posted to the group's public mailing list, or to a GitHub issue if the group uses GitHub.

## Decision Process

This group will seek to make decisions where there is consensus. Groups are free to decide how to make decisions (e.g. Participants who have earned Committer status for a history of useful contributions assess consensus, or the Chair assesses consensus, or where consensus isn't clear there is a Call for Consensus [CfC] to allow multi-day online feedback for a proposed course of action). It is expected that participants can earn Committer status through a history of valuable contributions as is common in open source projects. After discussion and due consideration of different opinions, a decision should be publicly recorded (where GitHub is used as the resolution of an Issue).

If substantial disagreement remains (e.g. the group is divided) and the group needs to decide an Issue in order to continue to make progress, the Committers will choose an alternative that had substantial support (with a vote of Committers if necessary). Individuals who disagree with the choice are strongly encouraged to take ownership of their objection by taking ownership of an alternative fork. This is explicitly allowed (and preferred to blocking progress) with a goal of letting implementation experience inform which spec is ultimately chosen by the group to move ahead with.

Any decisions reached at any meeting are tentative and should be recorded in a GitHub Issue for groups that use GitHub and otherwise on the group's public mail list. Any group participant may object to a decision reached at an online or in-person meeting within 7 days of publication of the decision provided that they include clear technical reasons for their objection. The Chairs will facilitate discussion to try to resolve the objection according to the [decision process](#decision).

It is the Chairs' responsibility to ensure that the decision process is fair, respects the consensus of the CG, and does not unreasonably favour or discriminate against any group participant or their employer.

## Chair Selection

Participants in this group choose their Chair(s) and can replace their Chair(s) at any time using whatever means they prefer. However, if 5 participants, no two from the same organisation, call for an election, the group must use the following process to replace any current Chair(s) with a new Chair, consulting the Community Development Lead on election operations (e.g., voting infrastructure and using [RFC 2777](https://tools.ietf.org/html/rfc2777)).

1.  Participants announce their candidacies. Participants have 14 days to announce their candidacies, but this period ends as soon as all participants have announced their intentions. If there is only one candidate, that person becomes the Chair. If there are two or more candidates, there is a vote. Otherwise, nothing changes.
2.  Participants vote. Participants have 21 days to vote for a single candidate, but this period ends as soon as all participants have voted. The individual who receives the most votes, no two from the same organisation, is elected chair. In case of a tie, RFC2777 is used to break the tie. An elected Chair may appoint co-Chairs.

Participants dissatisfied with the outcome of an election may ask the Community Development Lead to intervene. The Community Development Lead, after evaluating the election, may take any action including no action.

## Amendments to this Charter

The group can decide to work on a proposed amended charter, editing the text using the [Decision Process](#decision) described above. The decision on whether to adopt the amended charter is made by conducting a 30-day vote on the proposed new charter. The new charter, if approved, takes effect on either the proposed date in the charter itself, or 7 days after the result of the election is announced, whichever is later. A new charter must receive 2/3 of the votes cast in the approval vote to pass. The group may make simple corrections to the charter such as deliverable dates by the simpler group decision process rather than this charter amendment process. The group will use the amendment process for any substantive changes to the goals, scope, deliverables, decision process or rules for amending the charter.
