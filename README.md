# Source Code for NeuroLibre Version of Bastiaens Et Al.

View this repo's gh-pages hosted build [here](https://griffithslab.github.io/BastiaensAlphaModels_NeuroLibre/)

Origins of content:

- Github repo with modeling analysis code [here](https://github.com/GriffithsLab/Bastiaens2024_AlphaModels)
- Manuscript BiorXiv preprint [here](https://doi.org/10.1101/2024.03.01.583035)
- Overleaf latex source of preprint [here](https://github.com/JohnGriffiths/BastiaensAlphaModels_OverLeafSource)


Contributors to NeuroLibre porting work:

- John Griffiths
- Sorenza Bastiaens
- Jan Fousek
- Agah Karakuzu
- Yasmin Sheikh
- Barzany Ridha
- Justin Chang
- ...
- ...


Porting Process and Workflow:

- We used [l2m](https://github.com/agahkarakuzu/l2m.git), a LaTeX to MySTmd converter to convert the text of the original article, which was in a LaTeX source, to a markdown format.
- After LaTeX conversion, the excess code and any LaTeX file remnants were removed on the markdown file.
- The converted content was then mapped into the .md file containing the MyST article template.
- Figures and data from the original PDF and Jupyter workbooks were then mapped to the MyST article to reflect the original intended structure of the article with added MyST functionality.
- The compiled figures and .ipynb notebooks were sourced in our content file, and will appear as "secondary supplementary material section"
- We then used GitHub Actions to compile the MyST document upon every commit, which generated a website that’s hosted on GHpages using the files in this repository. This action is complimentary to building it locally, and allows users to see realtime changes with each commit upon compiling the document. 
