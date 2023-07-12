# STEM-EXP 2023 - Internship @ NYU VIDA: Quarto and OpenSpace

## Project Description

This internship was a part of my experience with the STEM-EXP program at The Peddie School. I interned for six weeks at the VIDA lab at NYU Tandon, under the mentorship of Ylva Selling. For this internship, my objective was to experiment with the tools in Quarto within OpenSpace. This is a pilot project for Quarto's integration into Openspace. I explored the capabilities and limitations of the various tools in Quarto, and worked with the OpenSpace API to integrate the program into the GUI.

## Softwares

### OpenSpace
![Image](https://raw.githubusercontent.com/OpenSpace/OpenSpace/master/data/openspace-horiz-logo-crop.png)

OpenSpace is an open source, non-commercial, and freely available interactive data visualization software designed to visualize the entire known universe and portray our ongoing efforts to investigate the cosmos. Bringing the latest techniques from data visualization research to the general public, OpenSpace supports interactive presentation of dynamic data from observations, simulations, and space mission planning and operations. More information on OpenSpace can be found on [their GitHub](https://github.com/OpenSpace/OpenSpace) or on [their website](https://www.openspaceproject.com/).

### Quarto

![Image](https://quarto.org/quarto.png)

Quarto is an open-source software built to improve the process of creating, publishing, and collaborating on scientific and technical documents. Its capabilities include support for various languages, such as Python, Observable JS, Julia, and R, as well as various outputs, such as HTML, MS Word, LaTeX, and more. In this project, I used a combination of Python and Observable JS code, although I had also experimented with other languages. I created outputs in both HTML and RevealJS presentation formats. More information on Quarto can be found on [their website](https://quarto.org/about.html).


## Getting Started

### Required Software

Softwares required to run the presentation are Quarto, OpenSpace, and the OpenSpace Developer GUI model. Quarto can be downloaded on [their website](https://quarto.org/about.html), and OpenSpace and the Developer GUI can be downloaded from their GitHub pages, found [here](https://github.com/OpenSpace/OpenSpace) and [here](https://github.com/OpenSpace/OpenSpace-WebGuiFrontend) respectively.

### Getting Started

Upon the first time running the program, the OpenSpace UI must be changed to developer mode. To do this, in the OpenSpace folder, head to `./data/assets/customization/gui.asset` and follow the instructions in the file.

Follow these steps to start the presentation:

1. Launch the OpenSpace application.
    - Use the `default_full` profile when prompted.
2. Open a command prompt from the `OpenSpace-WebGuiFrontend` directory.
3. In the terminal, run `npm start`.
4. In another command prompt, run `quarto preview revealjs.qmd --port 5668` in the `./quarto/Reveal-Presentation` directory.
5. If the presentation or UI doesn't load within OpenSpace, press F5 to reload the GUI.
6. View the presentation by interacting with the (Q) icon in the bottom bar.

## Quarto Experimentation

The folder labeled `Quarto Experimentation` contains the files I used to experiment with Quarto's features, such as the different languages and formats. It also includes a copy of my presentation before I integrated it with the OpenSpace UI. The contents of this folder can function independent of OpenSpace, unlike the final presentation.
