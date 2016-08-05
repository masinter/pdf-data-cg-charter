# [DRAFT] PDF and Open Data Community Group Charter

{NOTE to be removed: This Charter is work in progress. To submit feedback, please use https://github.com/masinter/pdf-data-cg-charter, or fork, edit, and make a pull request.}

{NOTE: when submitting, add URLs and time stamp
*   This Charter:
*   Previous Charter:
*   Effective data: 
}

## Goals

The PDF and Open Data Community Group will work to define methods of storing and retrieving (linked open) data to and from PDF files, elevating PDF from a "one-star" to "five-star" [open data format](http://5stardata.info/en/). Much of the world's data is already stored in PDFs, but the format's limited innate data retrieval capabilities hold back open data as a whole. Deliverables and specifications produced by this group will help overcome this limitation.

## Scope of Work

The Community Group will produce 
specifications and tooling targeted at producers and consumers of data, with the intention of standardizing the storage of (linked) (open) data within PDFs, without making the job of the publisher more difficult. This means that any method used to store data must be simple and versatile enough not to require modification of the data before storage, while still being easy for users to extract and interpret. Additionally, test cases should demonstrate a broad range of uses, mirroring the broad range of applications for data PDFs in the real world. Tooling needs to be adapted to cover the majority of cases out of the box.

* produce a guideline for PDF and data as outlined below
* resolve technical issues (see [BACKGROUND.md](BACKGROUND.md) for some examples.
* give feedback to ISO 32000 committee about requirements for PDF 2.1.
* (Possibly) review, produce, document, validate (some, one sample) software library for working with data in PDF.
* Propose a W3C Working Group to create a Recommendation based on the CG's initial report.

### Out of Scope

Out of the scope of this group:

* Requiring changes to PDF or XMP. The assumption for this group is that PDF exists, and is widely implemented.
* Reinventing the OCR wheel. OCR for PDF already exists, built into many products, and that capability can be leveraged to extract data if needed. Designing custom automatic data extraction and text recognition for open data is outside of this group's scope.
* Prescribing any specific implementation of open data in PDFs. While this group may identify implementations to  and test cases, it does not seek to push any particular implementation on producers or users.
* Discussion of the appropriateness of using PDF vs. other document formats. Although an interesting topic with a variety of opinions, the presumption for this work is to improve the data situation for those who choose to use PDF for whatever reason.

## Deliverables

### Specifications

We imagine a single document
* Guidelines for (Linked) (Open) Data and PDF

which includes the relevant material outlined in [BACKGROUND.md] and resolving the issues mentioned there. This document would detail methods of data storage in PDF documents, explain what tooling would have to accomplish, and create a set of guidelines for the basic process of storing and retrieving data to and from PDFs.

### Non-Normative Reports

The group may produce other Community Group Reports within the scope of this charter but that are not Specifications, for instance use cases, requirements, or white papers.

### Test Suites and Other Software

Test suites and example implementations of parts of the standard should be produced within the scope of the project. [PDFData](https://github.com/Aiybe/PDFData) is a "proof of concept" example, providing an implementation of data storage in PDF (accessible as a library, from the command line, or through a web service), as well as example datasets and documents for testing.

The group MAY produce test suites to support the Specifications. Please see the GitHub LICENSE file for test suite contribution licensing information.

## Dependencies or Liaisons

Liaison with ISO PDF group

## Community and Business Group Process

The group operates under the [Community and Business Group Process](https://www.w3.org/community/about/agreements/). Terms in this Charter that conflict with those of the Community and Business Group Process are void.

As with other Community Groups, W3C seeks organizational licensing commitments under the [W3C Community Contributor License Agreement (CLA)](http://www.w3.org/community/about/agreements/cla/). When people request to participate without representing their organization's legal interests, W3C will in general approve those requests for this group with the following understanding: W3C will seek and expect an organizational commitment under the CLA starting with the individual's first request to make a contribution to a group [Deliverable](#deliverables). The section on [Contribution Mechanics](#contribution-mechanics) describes how W3C expects to monitor these contribution requests.

## Work Limited to Charter Scope

The group will not publish Specifications on topics other than those listed under [Specifications](#specifications) above. See below for [how to modify the charter](#amendments-to-this-charter).

## Contribution Mechanics

Substantive Contributions to Specifications can only be made by Community Group Participants who have agreed to the [W3C Community Contributor License Agreement (CLA)](http://www.w3.org/community/about/agreements/cla/).

Specifications created in the Community Group must use the [W3C Software and Document License](http://www.w3.org/Consortium/Legal/2015/copyright-software-and-document). All other documents produced by the group should use that License where possible.

Community Group participants agree to make all contributions in the GitHub repo the group is using for the particular document. This may be in the form of a pull request (preferred), by raising an issue, or by adding a comment to an existing issue.

All Github repositories attached to the Community Group must contain a copy of the [CONTRIBUTING](https://github.com/w3c/licenses/blob/master/CG-CONTRIBUTING.md) and [LICENSE](https://github.com/w3c/licenses/blob/master/CG-LICENSE.md) files.

## Transparency

The group will conduct all of its technical work in public, using Git repository Issues, mailing list discussions, IRC, or (minuted) open meetings.
Meetings may be restricted to Community Group participants, but a public summary or minutes must be posted to the group's public mailing list, or to a GitHub issue if the group uses GitHub.

## Decision Process

This group will seek to make decisions where there is consensus. The Chair will assesses consensus; when consensus isn't clear t, there will be a Call for Consensus [CfC] to allow multi-day online feedback for a proposed course of action). After discussion and due consideration of different opinions, a decision should be publicly recorded (where GitHub is used as the resolution of an Issue).

If substantial disagreement remains (e.g. the group is divided) and the group needs to decide an Issue in order to continue to make progress, group members will be asked to produce one or more alternate forks of the relevant document(s). 

Any decisions reached at any meeting are tentative and should be recorded in a GitHub Issue or flagged in a email with Subject starting "DECISION: ".  Any group participant may object to a decision reached at an online or in-person meeting within 7 days of publication of the decision provided that they include clear reasons for their objection. The Chair(s) will facilitate discussion to try to resolve the objection according to the [decision process](#decision-process).

It is the Chairs' responsibility to ensure that the decision process is fair, respects the consensus of the CG, and does not unreasonably favour or discriminate against any group participant or their employer.

## Chair Selection

Ideally, Chair(s) should be selected by agreement of those who are willing to volunter chair. 

If there is not agreement, or if 3 participants, no two from the same organisation, call for an election, the group must use the process identified in http://w3c.github.io/cg-charter/CGCharter.html to replace any current Chair(s) with a new Chair, consulting the Community Development Lead on election operations.

1.  Participants announce their candidacies. Participants have 14 days to announce their candidacies, but this period ends as soon as all participants have announced their intentions. If there is only one candidate, that person becomes the Chair. If there are two or more candidates, there is a vote. Otherwise, nothing changes.
2.  Participants vote. Participants have 21 days to vote for a single candidate, but this period ends as soon as all participants have voted. The individual who receives the most votes, no two from the same organisation, is elected chair. In case of a tie, RFC2777 is used to break the tie. An elected Chair may appoint co-Chairs.

Participants dissatisfied with the outcome of an election may ask the Community Development Lead to intervene. The Community Development Lead, after evaluating the election, may take any action including no action.

## Amendments to this Charter

{NOTE: this only applies after the first charter is agreed.}

The group can decide to work on a proposed amended charter, editing the text using the [Decision Process](#decision-process) described above. The decision on whether to adopt the amended charter is made by conducting a 30-day vote on the proposed new charter. The new charter, if approved, takes effect on either the proposed date in the charter itself, or 7 days after the result of the election is announced, whichever is later. A new charter must receive 2/3 of the votes cast in the approval vote to pass. The group may make simple corrections to the charter such as deliverable dates by the simpler group decision process rather than this charter amendment process. The group will use the amendment process for any substantive changes to the goals, scope, deliverables, decision process or rules for amending the charter.
