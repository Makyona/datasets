---
annotations_creators:
- no-annotation
language_creators:
- found
languages:
- hr
licenses:
- cc-by-sa-3.0
multilinguality:
- monolingual
size_categories:
- 1B<n<10B
source_datasets:
- original
task_categories:
- sequence-modeling
task_ids:
- language-modeling
paperswithcode_id: null
pretty_name: HrWac
---

# Dataset Card for HrWac

## Table of Contents
- [Dataset Description](#dataset-description)
  - [Dataset Summary](#dataset-summary)
  - [Supported Tasks and Leaderboards](#supported-tasks-and-leaderboards)
  - [Languages](#languages)
- [Dataset Structure](#dataset-structure)
  - [Data Instances](#data-instances)
  - [Data Fields](#data-fields)
  - [Data Splits](#data-splits)
- [Dataset Creation](#dataset-creation)
  - [Curation Rationale](#curation-rationale)
  - [Source Data](#source-data)
  - [Annotations](#annotations)
  - [Personal and Sensitive Information](#personal-and-sensitive-information)
- [Considerations for Using the Data](#considerations-for-using-the-data)
  - [Social Impact of Dataset](#social-impact-of-dataset)
  - [Discussion of Biases](#discussion-of-biases)
  - [Other Known Limitations](#other-known-limitations)
- [Additional Information](#additional-information)
  - [Dataset Curators](#dataset-curators)
  - [Licensing Information](#licensing-information)
  - [Citation Information](#citation-information)
  - [Contributions](#contributions)

## Dataset Description

- **Homepage:** http://nlp.ffzg.hr/resources/corpora/hrwac/
- **Repository:** https://www.clarin.si/repository/xmlui/handle/11356/1064
- **Paper:** http://nlp.ffzg.hr/data/publications/nljubesi/ljubesic11-hrwac.pdf
- **Leaderboard:**
- **Point of Contact:** [Nikola Ljubešič](mailto:nikola.ljubesic@ffzg.hr)

### Dataset Summary

The Croatian web corpus hrWaC was built by crawling the .hr top-level domain in 2011 and again in 2014. The corpus was near-deduplicated on paragraph level, normalised via diacritic restoration, morphosyntactically annotated and lemmatised. The corpus is shuffled by paragraphs. Each paragraph contains metadata on the URL, domain and language identification (Croatian vs. Serbian).

### Supported Tasks and Leaderboards

[More Information Needed]

### Languages

Dataset is monolingual in Croatian language.

## Dataset Structure

### Data Instances

[More Information Needed]

### Data Fields

- sentence: sentences as strings

### Data Splits

[More Information Needed]

## Dataset Creation

### Curation Rationale

[More Information Needed]

### Source Data

#### Initial Data Collection and Normalization

[More Information Needed]

#### Who are the source language producers?

[More Information Needed]

### Annotations

#### Annotation process

[More Information Needed]

#### Who are the annotators?

[More Information Needed]

### Personal and Sensitive Information

[More Information Needed]

## Considerations for Using the Data

### Social Impact of Dataset

[More Information Needed]

### Discussion of Biases

[More Information Needed]

### Other Known Limitations

[More Information Needed]

## Additional Information

### Dataset Curators

[More Information Needed]

### Licensing Information

Dataset is under the [CC-BY-SA 3.0](http://creativecommons.org/licenses/by-sa/3.0/) license.

### Citation Information

```
 @misc{11356/1064,
 title = {Croatian web corpus {hrWaC} 2.1},
 author = {Ljube{\v s}i{\'c}, Nikola and Klubi{\v c}ka, Filip},
 url = {http://hdl.handle.net/11356/1064},
 note = {Slovenian language resource repository {CLARIN}.{SI}},
 copyright = {Creative Commons - Attribution-{ShareAlike} 4.0 International ({CC} {BY}-{SA} 4.0)},
 year = {2016} }
```

### Contributions

Thanks to [@IvanZidov](https://github.com/IvanZidov) for adding this dataset.
