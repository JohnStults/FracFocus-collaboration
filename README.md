# FracFocus-collaboration
# FracFocus-collaboration
# This file is meant to share python code data used to interperet a machine readable FracFocus database
# There are 3 primary databases used in this analysis.  The first is the FracFocus machine readable database
# The second is the screening manuscript data used for the Rogers et al. 2015 paper.
# The third is a database of all the suppliers and operators found in the FracFocus database
# All python code will be shared in this repository.  The actual manuscript screening data and the Roger et al. manuscript data are private and meant to be shared between collaborators on this project.

## There are 4 primary scripts as of right now which accomplish 4 different tasks
# 1) Spatial analysis of data script
# 2) Temporal analysis of data script.  This data is to be exported to .csv to be interpreted using R statistical analysis tool
# 3) Company analysis of data script.  This FracFocus data is cross-referenced with unique names of suppliers and operators in the FracFocus databse to analyze spatial and temporal trends in chemical of concern suppliers and operators using chemicals of concern
# 4) A composite "green score" for all wells in FracFocus.  This will cross reference chemical tox and mobility data from the rogers et al. manuscript

## Work to come
# There is a 4th database containing oil and gas production data from each state.  These can be cross-referenced with FracFocus database work to see if there are any interesting trends related to oil vs. gas producing counties and the types of hydraulic fracturing chemicals used in those counties.
