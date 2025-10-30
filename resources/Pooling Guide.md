---
layout: default
title: Library Pooling Guide
nav_order: 2
parent: Resources
has_children: true
---
# Sample Pooling Worksheet/Calculator
The goal of this sample pooling guide is to generate an even pool of sublibraries. To do this, we want to add an equal nM per library **and** an even volume of each library. 

{: .caution }
**Consult with CCG staff before using any resource with which you are unfamiliar.** These resources are provided for convenience and reference only; ensure that you understand all calculations and workflows before implementing them into your project, and always independently verify formulas, calculations, and results.

[Google Drive](https://docs.google.com/spreadsheets/d/1VeYFH3QpSOnLJZie2X68Q5Kkp6U9IDx4WxGPNYPbhWA/edit?usp=sharing) Sample Pooling/nM Conversion Calculator

### Instructions for Use

#### Step 1: Make a copy
Make your own copy of this sheet by clicking File → Make a Copy.
Be sure to give it a more helpful name than "Copy of nM Conversion Calculator: Markdown Edition."

#### Step 2: Enter your Qubit data
Enter your MEASURED SAMPLE CONCENTRATION in ng/μL (from Qubit) in column B.
If you have a wide range of sample concentrations, it may be helpful to sort them.
Groups of samples with very different concentrations can be split between multiple sheets.
In Google Sheets, select your data, right-click, and sort on Column B.

#### Step 3: Enter your TapeStation data
Enter your AVERAGE LIBRARY FRAGMENT LENGTH in BP (from TapeStation / BioAnalyzer / Gel) in Column C.

#### Step 4: Enter your desired library concentration (nM)
Enter your DESIRED LIBRARY CONCENTRATION in nM below.

{: .note}
Consult with your sequencing vendor on their minimum requirements for your sequencing project. Novogene requires 3.0 nM, and Ultima requires 3.0 nM.

#### Step 5: Enter your target subsample volumes (μL)
Enter 1–4 target subsample volumes in μL. Choose the value that best suits your samples.

#### Step 6: Enter the minimum value you feel comforatble pipetting (μL)
CCG Staff recommend pipetting at least 2.0 μL.

#### Step 7: Process samples that are highlighted as EV or IV
- EV: Excessive Volume. The volume required exceeds the target subsample size. Consider concentrating your sample.
- IV: Insufficient Volume. The volume required is below the minimum permitted in Step 5. Consider diluting your sample.

{: .caution }
Samples with excessively high (IV) or low (EV) concentrations can also be pooled separately.
To combine multiple pools, your "Desired nM" (Step 3) MUST BE EQUAL!

#### Step 8: Add the indicated amount of buffer to bring the pooled sample volume to the target pool volume.

#### (Optional) Step 9: Post-pooling Concentration
In some cases, you may need to concentrate (SpeedVac) samples after pooling.


If you notice a problem with this worksheet, email Richard: rbaker@calacademy.org
