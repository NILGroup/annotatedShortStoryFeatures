# Annotated Short Story Features
Experimental data for the article _Quantitative characteristics of human-written short stories_. Includes human-invented short stories and their annotation.

## Repository Contents

Simply two dataframes in JSON and CSV formats for the two annotators that participated in the experiment.

### Data Schema

Every row or object in the data frame is a sentence that was part of the stories invented by the human subjects

* **SENTENCE:** The textual representation, part of a human-invented story. It never spans more than a single sentence

* **DATE:** The date in which the data was gathered. All samples were gathered either the 23, 24 or 25 of May 2018

* **CLASS SEAT:** The physical location of the subject in the classroom. This number along with the date can be used to identify unique subjects

* **TYPE:** Whether the sentence represents a _plot description_ or a _plot action_ according to the annotator

* **PROTAGONIST IS AGENT:** Whether the protagonist of he story behaves with agency according to the annotator

* **PROTAGONIST IS AGENT:** Whether the protagonist of he story is the object of action according to the annotator

* **PREVIOUS ACTION:** The previous action in the story according to he annotator

* **DEPENDENCY [1,2 and 3]:** According to the annotators, and if present, the previous sentences that establish the causal occurrences that trigger this one

    code (4 spaces indent)
[links](https://wikipedia.org)

----
## changelog
* 01-Jul-2020 Initial commit 
