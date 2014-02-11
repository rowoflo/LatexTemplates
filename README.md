This is a collection of my LaTeX templates. This repo has git submodules in it. To clone this repo you use the following commands:

    >> git clone git@bitbucket.org:rowoflo/latex-templates.git MyTemplates
    >> cd MyTemplates
    >> git submodule init
    >> git submodule update

To add ROPackages submodule to a new template folder (NewFolder) run the following command from the MyTemplates folder

    >> git submodule add git@bitbucket.org:rowoflo/latex-packages.git NewFolder/ROPackages

To use a template copy and paste the contents into your working Latex folder. Remove the ROPackages folder and run:

    >> git submodule add git@bitbucket.org:rowoflo/latex-packages.git ROPackages


