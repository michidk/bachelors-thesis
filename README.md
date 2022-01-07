# Bachelor's Thesis

My Bachelor's Thesis in computer science, written at Technical University of Munich.
View current version as `.pdf` on [wiki.tum.de](https://wiki.tum.de/display/infar/BA%3A+Smartphone-Assisted+Virtual+Reality+Using+Ubi-Interact).

## Artifacts

The original repository is hosted on the public GitLab instance and mirrored to the university's private instance as well as GitHub.com.
The project is automatically built using the GitLab CI. The artifacts are published on [wiki.tum.de](https://wiki.tum.de/display/infar/%5B19SS+-+BA%5D+Smartphone-Assisted+Virtual+Reality+Using+Ubi-Interact).

## Study Evaluation Data

The raw results of the user study as well as the LimeSurvey export can be found in the `evaluation_data/` folder.

## Prerequisites

Dependencies are Texlive-Full (including biber and latexmk) and make.

## Building

To build the .pdf-file, execute:
`make pdf`

## Development

To launch latexmk in development-mode with live reloading, use:
`make watch`

## Commands

Additional commands are available:

To clean the output folder from built artifacts:
`make clean`

To remove the whole output folder:
`make purge`

## Credits

Based on the inofficial [tum thesis template](https://github.com/fwalch/tum-thesis-latex) by [Florian Walch and contributers](https://github.com/fwalch/tum-thesis-latex/graphs/contributors) - modified by me.
