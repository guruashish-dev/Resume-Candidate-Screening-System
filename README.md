# Resume Candidate Screening System

This repository contains a self-contained Jupyter notebook that screens and ranks resumes against a job description using an explainable NLP pipeline.

## What it does

- Cleans resume and job description text
- Extracts role-relevant skills with a transparent skill lexicon
- Computes TF-IDF cosine similarity between resumes and the job description
- Scores and ranks candidates
- Highlights missing skills for each candidate

## Files

- `resume_screening_system.ipynb` - the main notebook

## How to run

1. Open the notebook in VS Code or Jupyter.
2. Run the cells top to bottom.
3. Optional: place a CSV at `data/resumes.csv` with at least these columns:
   - `candidate_name`
   - `resume_text`

## Dependencies

The notebook uses:

- pandas
- numpy
- scikit-learn

## Notes

The default notebook includes a small sample dataset so it runs even without external files. Replace the sample data with a real resume dataset when you are ready to test on hiring data.
