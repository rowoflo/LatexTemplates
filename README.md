This is a collection of my LaTeX templates. This repo has git submodules in it. To clone this repo you use the following commands:

    >> git clone git@github.com:rowoflo/LaTeX_Templates.git MyTemplates
    >> cd MyTemplates
    >> git submodule init
    >> git submodule update

To add ROPackages submodule to a new template folder (NewFolder) run the following command from the MyTemplates folder

    >> git submodule add git@github.com:rowoflo/ROPackages.git NewFolder/ROPackages

Make sure the /usepackages{ROPackages/RO_syms} is included in the latex file.

To use a template copy and paste the contents into your working Latex folder. Remove the ROPackages folder and run:

    >> git submodule add git@github.com:rowoflo/ROPackages.git ROPackages
