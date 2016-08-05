# Background: PDF and Open Data

{NOTE: this document is still an outline}

## Bibliography

The following resources provide some background about PDF and its data capabilities:
* XMP ISO standard {TBD}
* RFC of PDF MIME type {TBD, point to new internet draft)
## PDF capabilities

PDF can store data above and beyond the presentation information:

* XMP: document metadata is stored in PDF using a syhtax based don an older style of RDF. It is a requirement of PDF/A 
* Tagged PDF
* File attachments
* Annotations

## Types of data which should be extractable

Complete tooling for open data in PDFs should be able to extract and act upon the following objects:

* Images, including captions.
* Data tables (see [CSV on the Web WG](https://www.w3.org/2013/csvw/wiki/Main_Page)).
* Document text, including markup.
* Tables of contents and indices for the document.
* Annotations (see [Annotations WG](https://www.w3.org/annotation/)).
* Citations (see [Force 11 guidelines](https://www.force11.org/group/joint-declaration-data-citation-principles-final)).
* Typed objects within the document, using RDFa and Schema.org to disambiguate and help machines understand document content.


## Issues

* What data goes where? The guide should discuss the use of various mechanisms available and correlate with the required data.
* Should there be a manifest (metadata which says where/how validated data appears)?
* What parts of PDF/A3 or PDF/UA should be referenced in the guidelines?

## Example implementations

* [PDFData](https://github.com/Aiybe/PDFData) is a "proof of concept" example, providing an implementation of data storage in PDF (accessible as a library, from the command line, or through a web service), as well as example datasets and documents for testing.

* [Tabula](https://github.com/tabulapdf/tabula) is a  sample implementation which makes other assumptions.

## Relationship to Accessibility and archivability

"Accessibility" is used to describe the usability of software and content by those with some form of disability. There are guidelines for software, authoring tools, and general erquirements for accessibility of Web Content (WCAG, Web Content Accessibility Guidelinese).



There are also W3C Notes that descibe best practices for various file formats, including  PDF:
* [Techniques for WCAG 2.0](http://www.w3.org/TR/2014/NOTE-WCAG20-TECHS-20140408/Overview.html)
* [PDF Techniques for WCAG 2.0](https://www.w3.org/TR/2014/NOTE-WCAG20-TECHS-20140408/pdf).


In addition, there is  a profile of PDF for accessibile content, called PDF/UA.

Accessibility and "open data" are related; think of "open data" as accessibility for robots. There is some overlap in the requirements for accessible content and the requirements for open data, including the ability to read document content in correct order, and the availability of text in Unicode.

Many of the organizations desiring or requiring publication (Government, Financial, Health Care, STEM publishing) require both PDF/UA and Open Data. 

Similarly, there is a profile of PDF, PDF/A, which was designed to hold archival documents, and the process of taking a PDF and making it suitable for long-term archiving.

The guidelines should explicitly idenetify the common requirements and solutions.
For example, PDF/UA requires all readab;e text be determinable by including a requiremenet for (readdability).
 

