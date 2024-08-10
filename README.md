# Description

A single-page, one-column resume for software developers. 
It uses the base latex templates and fonts to provide ease of use and installation when trying to update the resume. 
The different sections are clearly documented and custom commands are used to provide consistent formatting. The three main sections in the resume are education, experience, and projects.

### Motivation

This template is created for managing a resume on Google Docs as it was hard and changing any formatting was too difficult since it had to be applied in multiple places.

Most currently available templates either focus on two columns, or are multiple pages long that didn't work well for career fairs or online applications.

### Quick start

Get started quickly using [Overleaf](https://www.overleaf.com/latex/templates/software-engineer-resume/gqxmqsvsbdjf) template.

### Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex tushar_resume.tex
```

### Preview

![Tushar_Resume-1](https://github.com/user-attachments/assets/5b7ff015-ce0b-4533-8385-802f71a0f920)
![Tushar_Resume-2](https://github.com/user-attachments/assets/db2accd0-1502-4703-9e29-d4f26ffdc04f)


### Authority

All the data is owned by Tushar Bhardwaj.
