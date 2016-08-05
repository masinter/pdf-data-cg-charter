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



