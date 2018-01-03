# Wellington-Beamer-Theme
This Beamer Theme is designed to be clean and simple. The slides do not include any unnecessary structure, only the slide title and content. It is suitable for general purpose presentations when you want to get across just your ideas.

An example presentation demonstrating this theme can be seen here.

## Contact Details

Create by: Michael Kirker

Email: mkirker@uchicago.edu

Website: http://michaelkirker.net

Git repository: https://github.com/michaelkirker/Wellington-Beamer-Theme



## Repository Structure 

* /FiraSans/
  * Directory containing the font files
* beamerthemeWellington.sty
  * Beamer theme style file
* Example_Wellington_theme.tex
  * A simple example presentation detailing the key features of the 

## How to Use the Theme

For users that do not use Git, you can download the necessary files as a zip file.

If you are making a one-off presentation, copy the folder `/FiraSans/` and the file `beamerthemeWellington.sty` to the main folder of your presentation. Then include `\usetheme{Wellington}` in your Beamer presentation. As an example:

```latex
\documentclass[12pt]{beamer}		
% Preamble
\usetheme{Wellington}	

\begin{document}	
% Your presentation goes here
\end{document}
```

**Note that to compile the Beamer presentation using the Fira-Sans font, you need to use `XeLaTeX` rather than `PDFLaTeX`.**

For users that are likely to use this theme repeatedly on the same computer, you can alternatively add `beamerthemeWellington.sty` to your TeX search path, and `Fira-Sans` font to your operating system's font folder. These necessary files will then be assessable to any presentation you create on the computer, without the duplication of files across projects.