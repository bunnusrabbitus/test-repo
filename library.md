#Ribo-seq Library Preparation

###General notes:
1. Elution buffer: make the components yourself. Saisa has EDTA, which is stored in the fridge (#50 lower right corner)
2. Polysome buffer: use the components that Saisai has to prepare this buffer
3. Commercial RNase-free water is on Saisai's bench
  * Aliquot in 50 ml tubes before using.
4. Reagents for Riboseq are stored in a box in the 4ºC fridge #50 (bottom left corner)
5. Use the 'special' batch of A549 cells from LN2 (which one? Saisai)
6. Infected cells should be 80-90% confluent at the time of collection
7. Use 2 x 10 ml plate for each timepoint
8. Use new CHX for the lysis buffer
9. Use the old CHX powder in the 4ºC for PBS and sucrose
10. Prepare 60% sucrose stock
  * use this stock to prepare the 45%, 15%, and 1M sucrose solutions.

###Protocol:
#####DAY 1:
1. Wash cells twice with ice cold PBS + CHX
  * Use a 1/1000 dilution of the stock CHX solution
2. Tilt the dishes in the ice and remove the PBS + CHX
3. Add 400 µl of lysis buffer to the first plate
  * Lysis buffer is stored in -20ºC freezer (#53)
  * Need 400 µl of lysis buffer for each time point (see step 5)
  * Polysome buffer, 2% triton, CHX (1/500)
  * 100 µg/ml stock solutino of CHX is stored at 4ºC
4. Scrape the cells
5. Transfer the lysate to a second plate with same collection time. Scrape cells again.
6. Transfer lysate to 1.5 ml Eppendorf tube on ice.
7. Incubate on ice for 15 min.
8. Store samples at -80ºC until ready.

#####DAY 2:
1. Thaw samples on ice.
2. Transfer 100 µl of lysate from each timepoint to a separate Eppendorf for RNAseq
  *  Keep on ice.
3. Centrifuge lysate for Riboseq at 13,000 rpm in microcentrifuge at 4ºC, 10 min.
4. Transfer supernatant to new Eppendorf and discard pellet.
5. Add RNaseI 4 µl per plate or 8 µl per tube in this case, to the lysate.
  * RNaseI is stored in the -20ºC freezer.
6. Incubate with RNAseI in the cold room on a rotator for 1 hr (attach with tape).
7. Add 4 volumes of Trizol LS reagent to RNAseq aliquots (Total volume should be 500 µl)
  * Trizol is stored in the flammable closet beneath the chimical hood.
8. Incubate for 5 min at RT then transfer to -80ºC freezer.
9. Remove Riboseq samples from the rotator, place on ice and add 4 µl of SUPERase In to each sample.
10. Proceed to sucrose gradient protocol.

######Notes on sucrose cushion
* RNA binding protein protected RNA fragments are excluded when using a sucrose gradient. This is not the case if a sucrose cushion is used.
* I will not use this technique
* Prepare 1 ml per sample of sucrose in 15 ml tube
  * Add CHX 1/1000 to sucrose (Concentration 1 M).
* Transfer the sample to sucrose (505 µl).
  * If the sample is larger than 600 µl, it should be split into two tubes (this doesn't apply for a sucrose gradient).
* Place samples in the SW55TI rotor.
* Centrifuge at 54,000 rpm, for 6 h 30 min at 4ºC.
* The ribosome fraction will be pelleted.
* Remove the supernatant and dissolve the pellet in 1 ml of Trizol LS
* Store 500 µl of the sample at -80ºC as a back-up.

#####Preparing a sucrose cushion.
1. Prepare 1 M Sucrose from 60% sucrose solution stock
  * 60% sucrose = 60 g per 100 ml
  * 1 M sucrose = 34.2 g per 100 ml
  * So dilute 5.67 ml 60% stock in 4.33 ml polysome buffer to prepare 10 ml of 1 M sucrose
2. Add 1 ml of 1 M sucrose containing 100 µg/ml CHX (1/1000 dilution to the ultracentrifuge tube
  * Thickwall, polycarbonate, 3.5 ml, 13 x 51 mm (Beckman 349622).
3. Add < 600 µl of cell lysate on top of the 1 ml of sucrose (if more than 600 µl, split into two tubes).
4. Centrifuge at 54,000 rpm for 6.5 h with the SW55 Ti rotor
5. After centrifugation the pellet will be transparent.
6. Remove the sucrose.
7. Wash the pellet with polysome buffer without dislodging the pellet.
8. Dissolve the pellet in Trizol LS
9. Store samples at -80ºC for future library construction.
