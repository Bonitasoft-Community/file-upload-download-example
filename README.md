# File upload and download example

An example that illustrate how to allow user to upload and download a single document or a list of documents.
Also illustrate how to only allow certain type of files to be uploaded (e.g. only PDF files).

Process definition includes a reference to a document and to a list of documents (document with option "multiple" enable).

All files will be stored by Bonita BPM Engine in database.
Engine also saved the association between the process instance and documents content and version.

## Compatibility
This example has been created and built with Bonita BPM 7.1.5 Community edition.

It should be compatible with any newer version as well as Subscription edition.

## Known limitations
In order to implement optional upload of new document version a workaround is used. The workaround lead to duplication of existing document content when no new version of document is provided. This workaround is needed as steps operations are always executed and setDocument operation does not support null input.

File type validation is performed server side meaning that file need first to be upload to the server before being able to display warning message to the user.

## Issues
Reports issues and improvement request on GitHub tracker.
