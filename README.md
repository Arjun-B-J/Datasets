# Datasets

A collection of datasets and supporting materials, primarily centered around a
sample image dataset of US bank cheques along with related presentations and
architecture diagrams.

## Contents

### Cheque Data

The `Cheque Data/` directory contains sample cheque images organized into one
sub-folder per US bank. Files are stored as raster images (`.png`, `.jpg`,
`.jpeg`, `.gif`).

Banks included:

- BMO USA
- Bank of America
- Capital One
- Citigroup
- Comerica
- Fifth Third Bank
- Goldman Sachs
- HSBC Bank
- JPMorgan Chase
- KeyBank
- M&T Bank
- PNC Financial Services
- TD Bank
- Truist Financial Corporation
- U.S. Bancorp
- Wells Fargo & Co

Each folder typically holds a small handful of cheque samples (most banks have
between 1 and 10 images), useful for tasks such as cheque-image OCR
experimentation, document layout exploration, or visual reference.

### Root-level files

In addition to the cheque images, the repository includes a few presentation
and diagram files kept here for convenience:

- `Agentic AI Presentation.docx` / `Agentic AI Presentation.pdf` /
  `Presentation - Agentic AI.pptx` - materials on agentic AI.
- `Enterprise Generative AI.pptx` and `Enterprise Gen AI (Concise).pptx` -
  decks on enterprise generative AI.
- `Vector Squad.pdf` / `Vector Squad.pptx` - "Vector Squad" presentation.
- `nlp_→_mongo_db_prod_svg_architecture_diagram_with_star_pro_vector_db_mmr_rag.html`
  and the matching `.png` - an architecture diagram for an
  NLP -> MongoDB / vector-DB / MMR-RAG pipeline.

## Usage notes

- The cheque images are small samples intended for personal experimentation
  and demonstration. They are not a curated benchmark dataset.
- File names follow a short per-bank prefix convention (for example `JP1.png`
  for JPMorgan Chase, `WF3.jpg` for Wells Fargo, `BOA2.png` for Bank of
  America). Numbering is not guaranteed to be contiguous.
- No labels, annotations, or metadata files are included; the data is the
  images themselves.
