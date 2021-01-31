# Python_WLT-Demo

This Upload has the purpose to show the possibilities of utilization of the popular pylinac-Python-package for specific workflows. In this case: Winston-Lutz-Test-Analysis.

I compiled a modified version for you to test whether this package can be helpful in your clinic (Download-Link: https://drive.google.com/file/d/11HoV3sB2TwVn6NomHuok05VR6hcQY1gq/view?usp=sharing). If so, you can start with the not modified code (Link: https://github.com/jrkerns/pylinac)

After starting the application you have to navigate to the folder that has your Linac-DICOM-Images from a specific WLT stored. Note: The field has to be square and the BB round. After this you can specify the user for report signature. I changed our physicist names to user groups for this upload.

You can find Test-DICOMs from a TrueBeam-machine in the repo. Here is a Screenshot of the resulting report:
![Test Image 1](https://github.com/Kiragroh/Python_WLT-Demo/blob/master/Demo-Pic_WLT-Analyse_20200909-114829.png)

Legend: B->D: floor to ceiling direction; T->G: table to gantry direction; A->B: left to right direction looking to the gantry

Attention: This Demo uses a older version of pyLinac. Try the newest version to get even better results.
