# ClinVar Database

A skill for searching and analyzing clinical variant records in NCBI ClinVar.

## Capabilities

- Search variants by gene, genomic position, condition, or clinical significance.
- Query ClinVar through NCBI E-utilities.
- Retrieve summaries and full records, and work with bulk FTP data.
- Review ACMG/AMP-style classifications, assertion criteria, and review status.
- Investigate conflicting interpretations and annotate variant call sets.

## Included resources

The repository contains `SKILL.md` and supporting reference material for API usage and clinical significance interpretation. Review those references before automating queries or interpreting records.

## Usage

Use this skill for genomic research and variant annotation workflows. Validate query syntax, follow NCBI rate limits, identify the genome assembly and transcript context, and record the ClinVar accession and review status.

## Important

ClinVar submissions can conflict and may change as evidence evolves. A variant of uncertain significance is not a positive or negative diagnosis. Do not use an automated classification as the sole basis for patient care; clinical interpretation requires qualified genetics professionals and current evidence.
