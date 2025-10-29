---
layout: default
title: "QIAGEN QIAamp Micro"
ancestor: Protocols
parent: Extraction
---

# QIAGEN QIAamp Micro Kit
Adapted from [QIAGEN QIAamp DNA Micro Handbook](https://www.qiagen.com/ch/~/media/4D8DF38311F64606847546D1A40F0985.ashx).

{: .note }
If you are extracting DNA from small samples that are stored in EtOH, it is best to dry your sample of any EtOH before carrying out the extraction. You can do this by placing open tubes in the incubator; check on them every (approximately) 5 minutes.

### Gather the following materials _(per sample):_

#### Consumables
- (1) Eppendorf tube, locking, 1.5 mL, labeled
- (1) QIAGEN QIAamp MiniElute spin column, labeled (stored in fridge)
- (3) QIAGEN collection tubes
- (1) Sample storage tube (Eppendorf or screw-cap, 1.5–2 mL), labeled

#### Reagent aliquots, labeled (including your initials):
- Proteinase K <code style="color : blue">(small blue tube)</code>
- ATL buffer <code style="color : blue">(large blue tube)</code>
- AL buffer <code style="color : green">(green tube)</code>
- 100% ethanol, molecular-grade
- AW1 wash <code style="color : black">(white cap)</code>
- AW2 wash <code style="color : blue">(blue cap)</code>
- AE buffer <code style="color : olive">(yellow tube)</code>
- Carrier RNA (aliquots in freezer)


### Protocol
1. Cut up tissue into very small (~25 mg) pieces and add to the locking tube.
    Cut tissue on either a glass petri dish or a piece of parafilm. Be sure to use clean forceps and a clean scalpel/razor blade for each sample. You may reuse your forceps if utilizing the “Germinator”, but please return forceps to the dirty container when finished.
2. **Add 180 µL ATL Buffer** <code style="color : blue">(large blue tube)</code> to each 1.5 mL locking tube.
    The ATL Buffer may precipitate at room temperature. Incubate at 55°C for a few minutes and the precipitate will re-dissolve.
3. **Add 20 µL proteinase K** <code style="color : blue">(small blue tube)</code> to each locking tube.

{: .note}
When extracting insect tissues, we recommend increasing proteinase K volume to 60 µL per sample.

{:style="counter-reset:none"}
4. Vortex tubes and incubate at 55°C 4 hours–overnight. Use a rocking platform or thermal mixer, if available.
5. **Remove digested samples from the incubator and spin down.**

{: .caution}
Be mindful when opening your tubes as the lids can be dirty with solution after being inverted during incubation. If at any point your gloves become dirty, change them. Be very careful not to allow any cross-contamination of the samples.

{:style="counter-reset:none"}    
6. **Add 200 µL AL Buffer** <code style="color : green">(green tube)</code> to each tube. Use filtered tips here as the soapy consistency of this buffer can otherwise cause the liquid to travel up the pipette shaft and into the pipette.
7. **Add 200 µL 100% EtOH** to each tube. Use the same precautions as in step 6, including the use of filtered tips.
8. **Add 1 µL Carrier RNA** to each tube. Aliquots are in freezer. 
9. Ensure your tubes are locked closed. **Vortex thoroughly; spin down.**

{: .note} 
A white precipitate may form on addition of Buffer AL and ethanol. This precipitate does not interfere with the QIAamp Micro procedure.

{:style="counter-reset:none"}
10. Pipette the mixture including any preciptate (≈600 µL) to QIAamp MiniElute Spin Columns with collection tubes. 

    Use a P1000 with a filtered tip. When taking up the solution, avoid clumps of undigested tissue to prevent clogging the filter. Be sure not to touch or puncture the spin column filter with your pipette tip.

11. **Centrifuge spin columns 1 min at 6,000 g** (8,000 rpm). 

    When you remove the tubes from the centrifuge, verify that all liquid transferred from the spin column to the collection tube. Discard flowthrough into the Hazardous Waste container. If you see liquid still in the spin column, this means the filter in the column is clogged. Before proceeding, spin those clogged tubes again for 15 seconds at 13,000 x g (12,700 rpm). If the filter remains clogged, use a pipette to aspirate off and discard the supernatant that is in the spin column before proceeding.

12. Transfer spin columns to new 2 mL collection tubes.
13. **Add 500 µL AW1 Buffer** <code style="color : black">(white cap)</code> to spin columns.
14. **Centrifuge spin columns 1 min at 6,000 g** (8,000 rpm). Discard flowthrough.
15. Transfer the spin columns to new 2 mL collection tubes.
16. **Add 500 µL of AW2 Buffer** <code style="color : blue">(blue cap)</code> to each of the spin columns.
17. **Centrifuge spin columns 3 min at 20,000 g** (14,000 rpm). 

{: .caution}
When removing the spin columns from the centrifuge, be careful not to let the flowthrough come into contact with the spin column. It is important to dry the membrane of the QIAamp MiniElute spin column, since residual ethanol may interfere with subsequent reactions. If this happens, spin for 15 sec at the same speed to dry the column again. Discard flowthrough.

{:style="counter-reset:none"}
18. Transfer the spin columns to labeled, 2.0 mL screw-cap tubes. 

    It is very important at this step that you transfer the correct spin column to the correct labeled 2.0 mL storage tube! Be sure tubes are labeled with your extraction ID and extraction date.

19. **Add 50 µL AE Buffer** <code style="color : olive">(yellow tube)</code> to each of the spin columns.

{: .note} 
30 µL is the minimum elution volume required to saturate the filter. This lower volume may be advantageous if you expect your DNA yield to be very low.

{:style="counter-reset:none"}
20. **Incubate 3 min at 55 °C** to increase DNA yield.
21. **Centrifuge 1 min at 6,000 g** (8,000 rpm).
22. Discard your spin columns. Cap your tubes (with labels).
23. Quantify your DNA concentration using the [Qubit Flurometer](https://ccg-cas.github.io/protocols/qubit.html).
24. Analyze your DNA purity using the [Nanodrop](https://ccg-cas.github.io/protocols/nanodrop.html).

{: .warning }
<img src='https://github.com/CCG-CAS/gh-pages/blob/main/assets/GHS-corrosive.png?raw=true'
    alt="GHS Corrosive"  
    width='48'
    align='left'>
<img src='https://github.com/CCG-CAS/gh-pages/blob/main/assets/GHS-flammable.png?raw=true'
    alt='GHS Flammable'
    width="48"
    align='left'>
All guanidine hydrochloride/EtOH waste must be disposed of in its designated waste bottle. This includes all Buffer AL, EtOH, Buffer AW1, and Buffer AW2 waste.
