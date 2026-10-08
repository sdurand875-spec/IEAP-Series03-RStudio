# IEAP Series 03 — Data Wrangling and ANOVA

## 1. Project Overview

This repository contains the group assignment for Series 03 of the
IEAP RStudio course, focusing on data wrangling and analysis of variance
(ANOVA).

The main objective is to complete all the questions in the assignment
through a structured statistical analysis conducted in R.

The project combines statistical analysis, reproducible research,
scientific interpretation, and collaborative software development.

Our work includes a complete ANOVA pipeline, from data preparation
to the interpretation of statistical results.

Each step of the analysis is documented in a Quarto report, with
the corresponding R code and explanations.

## 2. Team Members

This project is carried out by:

- Sarah Durand
- Gaia Gassiole
- Vidusha Thebuwana

## 3. Project Objectives

The main objectives are to:

- Answer all the questions in Series 03.
- Perform the required data-wrangling operations.
- Conduct the appropriate statistical analyses, including ANOVA.
- Explain the analytical steps and interpret the results.
- Document the data sources and scientific references.
- Produce a reproducible Quarto report.
- Collaborate using Git and GitHub.
- Maintain a clear and meaningful Git commit history.
- Use branches to work on different questions in parallel.
- Merge completed work into the master document.
- Generate the final report in PDF format for submission on Moodle.

## 4. Repository Structure

The repository is organised around a master Quarto document and
supporting files.

```text
IEAP-Series03-RStudio/
├── README.md
├── LICENSE
├── IEAP-Series03-Rstudio.qmd      # master document
├── IEAP-Series03-Rstudio.pdf      # rendered report
├── Figure3_MT_vs_ID.pdf           # graph exported for publication (8 x 6 in)
├── workflow.qmd
├── challenges.qmd
├── Section/
│   ├── section_1_gaia.qmd         # 1.3 ANOVA
│   ├── section_2_vidusha.qmd      # 1.4 Linear regression by group
│   └── section_3_sarah.qmd        # 1.5 Graph and 1.6 PDF export
└── data/
    └── Results.txt
```

The structure may evolve as the project develops.

### Main files

- `README.md`: project description, objectives, and repository guide.
- `LICENSE`: licence associated with the project.
- `IEAP-Series03-Rstudio.qmd`: master Quarto document containing
  the complete report and incorporating the supporting documents.
- `workflow.qmd`: documentation of the team's Git workflow and
  collaboration strategy.
- `challenges.qmd`: documentation of the challenges encountered
  and lessons learned.
- `data/`: directory for the datasets required for the analysis.
- `Section/`: sub-documents included in the master document (one per team member).
- `IEAP-Series03-Rstudio.pdf`: final rendered report.
- `Figure3_MT_vs_ID.pdf`: graph of Movement Time as a function of ID, exported for publication.

## 5. Statistical Analysis

The statistical work follows a structured analytical pipeline.

The report will document the relevant steps, according to the
questions in the assignment:

1. Data preparation and data wrangling.
2. Exploration and description of the data.
3. Selection and implementation of the required statistical analyses.
4. ANOVA analysis, where required by the assignment.
5. Verification of the relevant statistical assumptions.
6. Presentation and interpretation of the results.
7. Scientific discussion and conclusions.

The exact analyses and methods will follow the requirements of
each question.

All relevant R code and answers will be included in the report.

## 6. Collaborative Workflow

Git and GitHub were used to organise the work and track changes.

The team:

- Use branches to work on different questions in parallel.
- Keep the `main` branch up to date.
- Use meaningful commit messages.
- Record progress throughout the project.
- Integrate completed work into the master Quarto document.
- Avoid modifying the same files simultaneously whenever possible.
- Check that the final document renders correctly.

The `main` branch will contain the final version submitted for
evaluation.

Further details are documented in `workflow.qmd`.

## 7. Reproducibility and Documentation

The final report includes:

- The authors and date.
- A link to this public GitHub repository.
- The complete code and answers to the assignment questions.
- Explanations of the analytical steps.
- Data sources and their URLs.
- Scientific references and their DOIs, where applicable.
- A description of the team's Git workflow.
- An analysis of challenges encountered and lessons learned.
- A checklist covering the grading criteria.

The project will aim to make the statistical analysis transparent
and reproducible.

## 8. Tools

The project uses the following tools:

- R
- RStudio
- Quarto
- Git
- GitHub

## 9. Project Status

**Current status:** Report completed.

All the questions of Series 03 have been answered. Each section was developed on its own branch and merged into `main` through Pull Requests. The final report is available in `IEAP-Series03-Rstudio.qmd` and its rendered version `IEAP-Series03-Rstudio.pdf`.

## 10. Final Deliverable

The final report is rendered as a PDF document and submitted on Moodle.

The `main` branch of this public repository will contain the
final version of the project.
