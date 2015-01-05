This is a collection of my LaTeX templates. Clone with

>> git clone git@github.com:rowoflo/LatexTemplates.git MyTemplates

To use:
Copy and paste the contents into your desired folder.

********************************************************************************
OLD STUFF
********************************************************************************
This is a collection of my LaTeX templates. This repo has git submodules in it. To clone this repo you use the following commands:

    >> git clone git@github.com:rowoflo/LatexTemplates.git MyTemplates
    >> cd MyTemplates
    >> git submodule init
    >> git submodule update

To add ROLatex submodule to a new template folder (NewFolder) run the following command from the MyTemplates folder

    >> git submodule add git@github.com:rowoflo/ROLatex.git NewFolder/ROLatex

Make sure the /usepackages{ROLatex/ROPackage} is included in the latex file.

To use a template copy and paste the contents into your working Latex folder. Remove the ROLatex folder and run:

    >> git init
    >> git submodule add git@github.com:rowoflo/ROLatex.git ROLatex
