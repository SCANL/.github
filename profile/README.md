# Welcome to the SCANL Github Organization!

Here, you will find tools and datasets related to the research done by SCANL.

# What is SCANL?

SCANL stands for the Source Code and Natural Language Laboratory. We are a diverse team of scientsits dedicated to studying the latent connection between source code behavior and the natural language elements used to describe that behavior. Feel free to visit https://www.scanl.org/ to learn more about who is part of the lab and to find more about our goals and research motivations.

# What is in this repository?

We have tools, datasets, and learning/educational resources. We will briefly describe each below, but refer to their individual repositories for more information.


| Name         | Description                             |
|--------------|-----------------------------------------|
| [Identifier Name Structure Catalogue](https://github.com/SCANL/identifier_name_structure_catalogue)| A catalogue of identifier name structures found in code and their significance to program behavior. This catalogue also covers various perspectives on how research literature characterizes identifier name meaning and behavior. |
| [SCALAR Tagger](https://github.com/SCANL/scanl_tagger)| A part-of-speech tagger designed to work on the [specialized phrase structure of identifiers](https://www.sciencedirect.com/science/article/abs/pii/S0164121220301680) (e.g., variable names).|
| [IDEAL](https://github.com/SCANL/IDEAL)| An identifier name appraisal and recommendation tool.|
| [srcML Identifier Getter Tool](https://github.com/SCANL/srcml_identifier_getter_tool)| A tool for collecting samples of identifier names from software systems using srcML. It can help you take statistically sound samples for research on identifier names.|
| [Project Sunshine](https://github.com/SCANL/ProjectSunshine)| An implementation of the [linguistic anti-patterns](https://doi.org/10.1007/s10664-014-9350-8) and soon-to-be merged with IDEAL to create a framework for identifier name appraisal and recommendation. |
| [Datasets](https://github.com/SCANL/datasets)| The current home of the [abbreviation study data set](https://ieeexplore.ieee.org/document/8918962), [the grammar patterns data set](https://www.sciencedirect.com/science/article/abs/pii/S0164121220301680), and the [ensemble tagger](https://ieeexplore.ieee.org/document/9491989) train/test data set|


We also host some (potentially modified) tools that other researchers made: [SWUM](https://github.com/SCANL/SWUM) has been modified by us to act primarily as a part-of-speech tagger. [POSSE](https://github.com/SCANL/POSSE) is the same; modified to help us use it as a part-of-speech tagger more easily. The Ensemble Tagger (mentioned above) uses it. The other public repositories are student projects, sample code, or misc tools that we use internally (i.e., not explicitly meant to be easy for others to use).

If you have trouble with any of our tools/datasets, please make an issue! In addition, if you like what we do, leave a star on the project-- it helps us know what to focus our maintenance efforts on and what kind of content people want to see most!
