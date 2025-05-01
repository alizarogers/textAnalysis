# NLP with TextAnalysis.jl in Julia

This repository is designated for a beginner's exploration into NLP with Julia. TextAnalysis is a package that is focused on cleaning up documents/corpuses. With the preprocessing complete, more advanced work can be done on the data.

There are two version of the main file: one with explanations and one without. Having both files in your fork may cause problems, so I suggest deleting the version that you do not want.

## File with Explanations

This file is meant to be helpful for folks that are not familiar with NLP.

It has extra markdown cells, for learning about NLP concepts. Additionally, it has a few step-by-step examples of how to clean up data in textAnalysis.

All of the contents of the set up file are also included here.

### File with Explanations - Packages Needed

- TextAnalysis
- OrderedCollections
- Printf

<br>
<br>

## Set Up File

This file contains <i>only</i> the set up of documents and their corpus, without the explanation cells and examples. It is meant to releive folks of set-up for NLP work. The following is defined in this file:

- **get_document()**: A function for processing documents, especially Project Gutenberg ebooks.

- **doc_list**: A list of StringDocuments, which are all of the ebooks that were loaded.

- **corpus**: A corpus that contains all of the ebooks.

- The following works, as StringDocuments:

<br>

| StringDocument Name | Title | Author |
|:---------------:|-----------|---------|
| wonderland | Alice's Adventures in Wonderland | Lewis Carroll |
| oz | The Wonderful Wizard of Oz | L. Frank Baum |
| secret_garden | The Secret Garden | Frances Hodgson Burnett
| treasure_island | Treasure Island | Robert Louis Stevenson |
| jungle_book | The Jungle Book | Rudyard Kipling |
| pinocchio | The Adventures of Pinocchio | C. Collodi |


### Set Up File - Package Needed
- TextAnalysis