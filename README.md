[README.md](https://github.com/user-attachments/files/33776378/README.md)
# Media Research Toolkit

Open resources for transparent media and communication research: a news-framing codebook, sampling and preregistration templates, an exploratory digital-media survey, a semi-structured interview guide, and a dependency-free agreement checker.

## Status
Initial research and teaching starter repository. No adoption, validation, stars, or download claims are made. Instruments are illustrative and require adaptation, piloting, and appropriate ethics review before use in research.

## Quick start
1. Define a research question and select a theoretical lens in `templates/study-plan.md`.
2. Specify the population, sampling frame, exclusions, and unit of analysis before collection.
3. Adapt `templates/content-analysis-codebook.md`; train coders on a pilot subset and record revisions.
4. Use the survey or interview guide only after contextual adaptation and pilot testing.
5. Run `python3 scripts/agreement.py examples/coder_ratings.csv` to reproduce a small synthetic agreement example.

## Contents
- `templates/study-plan.md`: research design and preregistration worksheet.
- `templates/content-analysis-codebook.md`: operational definitions and coding rules.
- `templates/digital-media-survey.md`: unvalidated exploratory questionnaire.
- `templates/interview-guide.md`: qualitative interview prompts.
- `templates/data-management.md`: reproducibility and participant protection checklist.
- `scripts/agreement.py`: percent agreement and unweighted Cohen's kappa for two coders, one nominal variable.
- `examples/coder_ratings.csv`: entirely synthetic demonstration data.
- `QUALIFICATION.md`: a contribution-based application draft.

## Methodological positioning
The news codebook draws on framing as selection and salience; the survey explores media-use motivations and perceived credibility. These are starting concepts, not validated measures or automatic evidence for a theory. Consult original theoretical sources and relevant validated instruments in a literature review. Do not infer causality from a cross-sectional convenience survey. Report missingness, coder disagreement, sampling limits, and revisions openly.

## Reuse
MIT License covers the original resources in this repository. It grants no rights to third-party media, platform data, or participant responses. No real participant data are included.

## Publish on GitHub
Create a repository named `media-research-toolkit` in your own GitHub account, then upload this folder's contents. Choose a description such as: “Open templates and reproducibility tools for media and communication research.” Review all files before publication. Replace the citation metadata placeholders with your preferred author information and the actual repository URL.
