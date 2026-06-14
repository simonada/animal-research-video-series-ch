# Forschung mit Tieren in der Schweiz

This repository contains the source code and content for the website accompanying the video series **"Forschung mit Tieren in der Schweiz"** ("Research with Animals in Switzerland").

The project aims to promote transparent and evidence-based communication about animal research in Switzerland by addressing questions submitted by members of the public and answered by researchers and experts.

## About the Project

The video series was developed by **Simona Doneva** and **Tosca Dalessi** during their PhD studies at the University of Zurich.

More than 400 questions submitted by people in Switzerland formed the basis of the project. Using modern text analysis methods, including word embeddings, similar questions were grouped together and used to identify the main themes addressed in the videos.

The series covers topics such as:

- The purpose and regulation of animal research
- Animal welfare
- Researchers' perspectives
- Ethical considerations
- Alternatives to animal experimentation

## Website

The website is built with [Quarto](https://quarto.org/) and is available in German and English.

## Repository Structure

```text
.
├── _quarto.yml
├── index.qmd
├── about.qmd
├── about-project.qmd
├── videos.qmd
├── topics/
├── en/
├── images/
├── styles.css
└── docs/
```

## Building the Website

Install Quarto and render the website locally:

```bash
quarto render
```

Preview the website:

```bash
quarto preview
```

## Deployment

The website is deployed using GitHub Pages.

After rendering, the generated site is stored in the `docs/` directory and can be published directly through GitHub Pages by selecting:

```text
Settings → Pages → Deploy from branch → main → /docs
```

## Acknowledgements

This project was supported by:

- Vice President Research Office, University of Zurich
- Office for Animal Welfare and 3R, University of Zurich
- UZH Communications
- Life Science Zurich

## Contact

For questions or comments, please contact the project team through the contact information provided on the website.