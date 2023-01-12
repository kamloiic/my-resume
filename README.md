## preview

#### résumé

you can see [PDF](https://raw.githubusercontent.com/kamloiic/my-resume/main/examples/resume.pdf)

| Page | 
|:---:|
| [![résumé](https://raw.githubusercontent.com/kamloiic/my-resume/main/examples/resume.png)](https://raw.githubusercontent.com/kamloiic/my-resume/main/examples/resume.pdf)  | 

## quick start

* [**edit résumé on overleaf.com**](https://www.overleaf.com/latex/templates/awesome-cv/tvmzpvdjfqxp)

## how to use

#### requirements

a full tex distribution is assumed or can be found [here](https://tex.stackexchange.com/questions/55437/how-do-i-update-my-tex-distribution) 

if you don't want to install the dependencies on your system, this can also be obtained via [docker](https://docker.com).

#### usage

at a command prompt, run

```bash
xelatex {your-cv}.tex
```

or using docker:

```bash
docker run --rm --user $(id -u):$(id -g) -i -w "/doc" -v "$PWD":/doc thomasweise/texlive make
```

in either case, this should result in the creation of ``{your-cv}.pdf``


## credit

[**awesomecv**](https://github.com/posquit0/Awesome-CV) 

[**latec**](https://www.latex-project.org) 

[**latex fontawesome**](https://github.com/furl/latex-fontawesome) 

[**roboto**](https://github.com/google/roboto) 

[**sourcesanpro**](https://github.com/adobe-fonts/source-sans-pro) 
