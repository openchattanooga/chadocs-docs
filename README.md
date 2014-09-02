# chadocs-docs

Document repository and index source for [chadocs](https://github.com/openchattanooga/chadocs).

New documents submitted to this repository will be automatically fed into chadoc's document index about every 15 minutes.

## Metadata 

Please do your best in regards to adding metadata to the document. Please have a `Title` metadata item, for instance.

The following fields are accepted for now:

|   Field              |                Description                  |                    Example                  |
|----------------------|---------------------------------------------|---------------------------------------------|
| `author`             | Author of document.                         | `Some Person`                               |
| `title`              | Title of document.                          | `Some Document`                             |
| `date`               | Document date.                              | `2014-01-01T00:00:00`                       |
| `keywords`           | Keywords relevant to document content.      | `some,document,keyword`                     |



## Adding Documents

### Add Metadata

Before you start a pull request or attach a document to be submitted via an issue, please add the relevant metadata.

### Start A Pull Request Or Issue
Start a pull request or issue. If you want to send a pull request, make sure your document is in the `document` subdirectory in the repo. For purposes pertaining to metadata PDFs, doc, and odt formats are accepted. Although plain text is indexible, the plain text file won't have metadata associated with it.
