# Custom Style for PubMed Batch Citation Matcher
Custom .CSL style file that will output citations in a format accepted as input to PubMed's Batch Citation Matcher
--------------------------------------------------
[![license](https://img.shields.io/badge/license-CC%20BY%20SA%203.0-blue.svg)](https://github.com/citation-style-language/styles#licensing)


When using PubMed's [Batch Citation Matcher (BCM)](https://pubmed.ncbi.nlm.nih.gov/batchcitmatch/) to retrieve PMIDs for multiple citations, PubMed BCM needs the following citation input format:

journal_title|year|volume|first_page|author_name|your_key|

See the [PubMed BCM documentation](https://pubmed.ncbi.nlm.nih.gov/help/#batch-citation-matcher) for more details and information.

custom-style-for-pubmed-batch-citation-matcher.csl
--------------------------------------------------

The custom style in this repository will work in Zotero to output a "Bibliography" in a format that can be pasted into the PubMed BCM.

It was created using the [CSL Visual Style Editor](https://editor.citationstyles.org/visualEditor/) and manual editting.


To use in Zotero
--------------------------------------------------

Install the custom style:

Download the style from this repository to your computer

Install it with the Zotero Style manager ([Zotero Documentation: Installing Additional Styles](https://www.zotero.org/support/styles#alternative_installation_methods))
- Open Zotero Settings --> Cite --> Styles, and use the Style Manager
- Click the “+” button and locate custom-style-for-pubmed-batch-citation-matcher.csl on your computer

Restart Zotero

Select desired articles and create a Bibliography ([Zotero Documenation: Creating Bibliographies](https://www.zotero.org/support/creating_bibliographies#right-click_to_create_citationbibliography))
- Right-click on the selected citations.
- Select the custom style.
- Select Create Bibliography from Selected Item(s).
- Select Copy to Clipboard.

Paste the "bibliography" into a document to save for later, or directly into the PubMed BCM.
