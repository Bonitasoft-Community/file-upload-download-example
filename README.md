Note: in order to download the example, go to the release section and download the .bos file. bos file can be imported in Bonita Studio using "File", "Import..." menu.

# File upload and download example

An example that illustrate how to allow user to upload and download a single document or a list of documents.
Also illustrate how to only allow certain type of files to be uploaded (e.g. only PDF files).

Process definition includes a reference to a document and to a list of documents (document with option "multiple" enable).

All files will be stored by Bonita Engine in database.
Engine also saved the association between the process instance and documents content and version.

## Compatibility
This example has been created and built with Bonita BPM 7.8.3 Community Edition.

It should be compatible with any newer version as well as Entreprise Edition.

## Known limitations
File type validation is performed server side meaning that file need first to be upload to the server before being able to display warning message to the user.

## Issues
Reports issues and improvement request on GitHub tracker.
