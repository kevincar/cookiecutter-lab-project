# Lab project directory

This cookiecutter provides an initial layout for laboratory projects that
consist of one or many experiments

## Usage

Install cookiecutter
```bash
pip install cookiecutter
```

Initialize a new lab project
```bash
cookiecutter http://github.com/kevincar/cookiecutter-lab-project
```

## Project directory overview

```
{{project-name}}        # projects each get their own folder <- these can be git repos
│
├── presentations
│   │
│   ├── abstracts
│   │
│   ├── posters
│   │
│   └── figures         # Figures for this project can eithe be project specific, or links to figures owned by the
│                       # project's experiments
│
├── ref                 # Directory for BibTex, EndNote, or other reference files for reference managment
│
│
├── reports             # markdown/LaTeX documentation of the project to prepare final manuscript. This can be compiled
│                       # from reports and documentation from reports in the exp directory
│
└── exp                 # Folder that houses all experiments used in the project
```

[See the exp cookiecutter](https://github.com/kevincar/cookiecutter-exp) for creating new experiments to place in the `exp`
folder
