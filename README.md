# pdfrfc

Documents and files related to RFCs in PDF.

'pdfrfc' is the an Internet Draft for consideration by the RFC
Editor's informal working group on RFC format, specifically for the
PDF rendition.

'pdfmime' is a proposed update to RFC 3778 that registers the
application/pdf MIME type.

Eventually, the project might contain

* test cases
* sample code

## Creating Internet Drafts

Use xml2rfc to convert .xml file into .html and .txt

 `xml2rfc pdfrfc.xml --text --html`

Periodically submit an Internet Draft at https://datatracker.ietf.org/submit/
to make a new version of http://tools.ietf.org/html/draft-hansen-rfc-use-of-pdf

Be sure to update the file version number in the xml file before submitting.

## Viewer

Best if you use xml2rfc but here are links that will convert the
latest master branch:

* [pdfrfc to HTML](http://xml2rfc.tools.ietf.org/cgi-bin/xml2rfc.cgi?url=https://raw.githubusercontent.com/masinter/pdfrfc/master/pdfrfc.xml&modeAsFormat=html/ascii&type=ascii)
* [To PDF via HTML](http://xml2rfc.tools.ietf.org/cgi-bin/xml2rfc.cgi?url=https://raw.githubusercontent.com/masinter/pdfrfc/master/pdfrfc.xml&modeAsFormat=html/pdf&type=ascii). Note this conversion doesn't meet many of the proposed requirements.
* [To TEXT](http://xml2rfc.tools.ietf.org/cgi-bin/xml2rfc.cgi?url=https://raw.githubusercontent.com/masinter/pdfrfc/master/pdfrfc.xml&modeAsFormat=txt/ascii&type=ascii)
* [PDF via TEXT](http://xml2rfc.tools.ietf.org/cgi-bin/xml2rfc.cgi?url=https://raw.githubusercontent.com/masinter/pdfrfc/master/pdfrfc.xml&modeAsFormat=txt/pdf&type=ascii)
