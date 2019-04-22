# Bachelor Thesis
My Bachelor's Thesis in computer science, written at Technical University of Munich.

## Prerequisites
Dependencies are Texlive-Full (including biber and latexmk) and make.
I am using [this Docker-image](https://github.com/michidk/texlive-docker) to build the pdf.

## Building
To build the .pdf-file, execute:
```make pdf```

## Development
To launch latexmk in development-mode with live reloading, use:
```make watch```

## Commands
Additional commands are available:

To clean the output folder from built artifacts:
```make clean```

To remove the whole output folder:
```make purge```



## Credits

Based on the inofficial [tum thesis template](https://github.com/fwalch/tum-thesis-latex) by [Florian Walch and contributers](https://github.com/fwalch/tum-thesis-latex/graphs/contributors) - modified by me.