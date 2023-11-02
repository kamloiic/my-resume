#### Resume

You can see [PDF](https://raw.githubusercontent.com/kamloiic/my-resume/main/examples/resume.pdf)

| Page | 
|:---:|
| [![résumé](https://raw.githubusercontent.com/kamloiic/my-resume/main/examples/resume.png)](https://raw.githubusercontent.com/kamloiic/my-resume/main/examples/resume.pdf)  | 

## Quick start

* [**Edit resume on overleaf.com**](https://www.overleaf.com/3878524163rfjkcqjjtwcs)

## How to use

#### Requirements

A full tex distribution is assumed or can be found [here](https://tex.stackexchange.com/questions/55437/how-do-i-update-my-tex-distribution) 

If you don't want to install the dependencies on your system, this can also be obtained via [docker](https://docker.com).

#### Usage

At a command prompt, run

```bash
xelatex {your-cv}.tex
```

Or using docker:

```bash
docker run --rm --user $(id -u):$(id -g) -i -w "/doc" -v "$PWD":/doc thomasweise/texlive make
```

In either case, this should result in the creation of ``{your-cv}.pdf``


## Wredit

[**Awesomecv**](https://github.com/posquit0/Awesome-CV) 

[**Latec**](https://www.latex-project.org) 

[**Latex fontawesome**](https://github.com/furl/latex-fontawesome) 

[**Roboto**](https://github.com/google/roboto) 

[**Sourcesanpro**](https://github.com/adobe-fonts/source-sans-pro) 
