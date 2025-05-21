# annot

Analysis of manual annotation of gendered and gender biased language in archival metadata descriptions using the [brat rapid annotation tool](https://brat.nlplab.org).

#### Annotation Taxonomy
```
Gendered and Gender Biased Language
├── Person Name
│   ├── Unknown
│   ├── Non-binary
│   ├── Feminine
│   └── Masculine
├── Linguistic
│   ├── Generalization
│   ├── Gendered Pronoun
│   └── Gendered Role
└── Contextual
    ├── Empowering
    ├── Occupation
    ├── Omission
    └── Stereotype
```

#### Table of Contents
* [Directory Structure](#directory-structure)
* [Contents](#contents)
* [Associated Resources](#associated-resources)
* [License and Citation](#license-and-citation)

## Directory Structure
```
annot/
├── AnnotationInstructions.docx
├── data/  
│   ├── analysis_data/ (**hidden in GitHub repo**)
│   ├── iaa/
│   └── sample/
├── notebooks/
│   ├── aggregating_data/
│   ├── analyzing_data/
│   ├── cleaning_metadata/
│   └── preparing_data
├── .gitignore
└── README.md
```

## Contents

* `AnnotationInstructions.docx`: instructions given to the annotators for labeling archival metadata descriptions in brat (includes the annotation taxonomy)
* `data:`
  * `data/sample:` directory with a sample of the annotated data as a CSV file
  * `data/iaa:` inter-annotator agreement scores per annotator and per label
  * ***Note:** annotated data *will be* uploaded to this directory after further analysis*
* `notebooks:` code written to prepare, aggregate, and analyze the annotated data, and to clean additional metadata fields associated with the annotated data (e.g., date of material, language of material)

## Associated Resources

* Data source: [Archives Online, Centre for Research Collections, University of Edinburgh](archives.collections.ed.ac.uk)
* Dataset preparation repository: [annot-prep](https://github.com/thegoose20/annot-prep)
* Datasets: available [here](https://doi.org/10.7488/ds/7540) in the Edinburgh DataShare
* Publications:
  * Research methodology: [Situated Data, Situated Systems: A Methodology to Engage with Power Relations in Natural Language Processing Research](https://aclanthology.org/2020.gebnlp-1.10/)
  * Annotation taxonomy and data creation: [Uncertainty and Inclusivity in Gender Bias Annotation: An Annotation Taxonomy and Annotated Datasets of British English Text](https://aclanthology.org/2022.gebnlp-1.4/)

## License and Citation
[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)

```
@inproceedings{havens-etal-2022-uncertainty,
    title = "Uncertainty and Inclusivity in Gender Bias Annotation: An Annotation Taxonomy and Annotated Datasets of {B}ritish {E}nglish Text",
    author = "Havens, Lucy  and
      Terras, Melissa and
      Bach, Benjamin  and
      Alex, Beatrice",
    booktitle = "Proceedings of the 4th Workshop on Gender Bias in Natural Language Processing (GeBNLP)",
    month = jul,
    year = "2022",
    address = "Seattle, Washington",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.gebnlp-1.4",
    pages = "30--57"
}
```
