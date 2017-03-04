# EASE LaTeX templates
Unofficial LaTeX template for the "Requirements Analysis Document" and the "System Design Document",
part of the project of the course **Essentials of Applied Software Engineering** of the [Technical University of Munich](https://www.tum.de/), on [edge.edx.org](https://edge.edx.org/).
They try to imitate the official templates for Microsoft Word.

The images are property of the [Technical University of Munich](https://www.tum.de/).

## How to add figures and tables etc?

You may find some snippets at the end of each document that will help you. The figures should be places in the `figures/` directory.

## LaTeX or XeLaTeX?

The provided PDF examples are compiled with XeLaTeX, using the [CMU Bright font](https://fontlibrary.org/en/font/cmu-bright). By default, this is disabled, in order to support legacy LaTeX. In order to use it, **replace**:

```tex
\renewcommand{\familydefault}{\sfdefault}
```

with:

```tex
\usepackage{fontspec}
\setmainfont[Mapping=tex-text]{CMU Bright}
```

See the comments in the preamble for details.

## Contribute

Please make sure that this templates maps the current state of the officially provided templates. If you find any changes, please create a Pull Request to contribute them back to this repository.
