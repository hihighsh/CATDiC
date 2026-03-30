# Central Asian Turkic Discourse Corpus (CATDiC)

## Overview

The Central Asian Turkic Discourse Corpus (CATDiC) is a pilot corpus of discourse data from five Turkic languages:

- Uzbek  
- Kazakh  
- Turkmen  
- Kyrgyz  
- Uyghur  

Each dataset consists of approximately 2 minutes and 15 seconds of annotated dialogue.

The corpus includes:

- Video recordings (.mp4)
- Audio recordings (.wav)
- ELAN annotation files (.eaf)
- Metadata files

However, Turkmen data is excluded due to consent restrictions.
This pilot release provides a structured and reusable dataset for discourse analysis and comparative research on Central Asian Turkic languages.

---

## Annotation

The corpus is annotated using ELAN with multiple tiers.

### Tier structure

Each tier name consists of an annotation label and a speaker identifier, separated by the "@" symbol.

The part before "@" indicates the type of annotation, and the part after "@" indicates the speaker ID.

Speaker identifiers vary across recordings and are used as anonymized labels.  
Detailed speaker information is provided in `metadata/speakers.csv`.

### Tiers

- `number@X`: annotation index for speaker X
- `translation_jp@X`: Japanese translation for speaker X
- `transcription@X`: utterance-level transcription for speaker X
- `segmentation@X`: segmentation for speaker X
- `morpheme@X`: morpheme-level segmentation for speaker X
- `gloss@X`: glossing for speaker X
- `DA_dim@X`: discourse annotation (dimension) for speaker X
- `DA_func@X`: discourse annotation (function) for speaker X

### Notes

This is a pilot dataset.  
Some annotation layers may be incomplete or exploratory.

Speaker identifiers are anonymized, and sensitive information has been removed or generalized where necessary.

---

## Metadata

The corpus includes structured metadata:

- `metadata/metadata.csv`  
  File-level information (language, duration, file names, etc.)

- `metadata/speakers.csv`  
  Anonymized speaker information

## File Structure

```
corpus/
├── README.md
├── LICENSE
├── metadata/
│   ├── metadata.csv
│   └── speakers.csv
├── data/
│   ├── uzbek/
│   ├── kazakh/
│   ├── turkmen/
│   ├── kyrgyz/
│   └── uyghur/
```
---

## Usage

CATDiC is intended for:

- Discourse analysis  
- Turkic linguistics  
- Comparative studies  
- Annotation research  

Users are encouraged to verify annotation layers depending on their research purposes.

---

## Data Access

The dataset is available on Zenodo:

https://doi.org/XXXX

---

## License

This dataset is released under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license.

You are free to:

- Share  
- Adapt  

Under the condition that appropriate credit is given.

---

## Acknowledgements

We thank all participants who contributed to the recordings.

---

## Version

This is CATDiC version 1.1 (pilot release).  

Future versions may include:

- Improved segmentation  
- Additional annotation layers  
- Expanded data size  
