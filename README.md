- [LaTeX-MSCS-Thesis-Project-Format](#latex-mscs-thesis-project-format)
- [Features](#features)
- [Contributing](#contributing)
- [Getting Statted](#getting-statted)
  - [Software](#software)
  - [Build your project](#build-your-project)
  - [Project structure](#project-structure)

# LaTeX-MSCS-Thesis-Project-Format

This repository provides a LaTeX a template for writing a master's thesis or project. In particular, this document correctly adheres to all of Weber State University's formatting standards for Computer Science Department as of December 2010. If you are using this template to submit a thesis to a different institution or department, please review your department's submission guidelines as this template may not be applicable.

# Features

The template is relatively robust, handling the automatic generation of the table of contents, list of figures, list of tables, bibliography, and acronyms (when appropriate). A cover page and acknowledgments section are also included.

# Contributing

Also included is a minimal working example of the template which illustrates several handy features that someone new to LaTeX can use for their dissertation. Among these are inserting algorithms, figures, subfigures, tables, and references. Users are encouraged to add helpful tips, tricks, and techniques to the minimum working example and submit a pull request. If I feel that the added technique is especially useful to LaTeX beginners, I will merge it into the master branch.

More than likely I will not merge in any change that impacts the overall format of the template. However, feel free to fork this and modify it to meet the guidelines of your own university or academic department. At the very least it should serve as a fairly robust starting point.

This guide was originally created by Eli Hooten, then revised by in early 2021 by Haley Adams. The current version of this guide was updated in Septermber 2021 by Hugo Valle.

# Getting Statted

## Software

First, you need to download a software compiler. I suggest to use [MIkTEX](https://miktex.org/). The initial intastallation will take a few minutes. The package includes `TeXworks` which is a Latex editor.

Next, you need to fork the repository if you want to source control your code (why wouldn't you?):

<https://github.com/hugo-valle/wsu-mscs-template>

If you need help, see the `How to fork` a repo [link](https://docs.github.com/en/get-started/quickstart/fork-a-repo)

Alternatevely, you can also [download the zip file](https://documentation.alphasoftware.com/pages/HowTo/Other/Download%20GitHub%20Project.xml) with all the required files.

## Build your project

Locate the folder where you downloaded your project and open `MSCSThesisProjectFormat.tex` using the `TeXWorks` editor.

This is the main file that controls the project. Next, compile the project by cliking the green play button on the top left of the gui. This initial build, will take several minutes. TeXworks needs to download all packages required to build the project. Just accept all the changes.

## Project structure

The project is organized as follows:

- `MSCSThesisProjectFormat.tex` : In this file, you only need to edit/include your name as well as those of your committee members.
- `MSCSThesisProjectFormat.pdf` : This is the sample pdf with all the default information.
- `MyLibrary.bub`: This file contains your bibliography.
- Other files: The `sfchap.sty` and `sfsection.sty` are style files used by the project. The `tableTest.tex` contains a sample table. This table is included in one of your chapter files.
- `Figures`: This folder contains any figures used in your report.
- `Sections`: This folder contains the individual sections/chapter files of your report
  
Note: Remember, `MSCSThesisProjectFormat.tex` is your MAIN file. This is the file you need to recompile every time you make a change.
This includes the bibliography file or any file in the `Sections` folder.
