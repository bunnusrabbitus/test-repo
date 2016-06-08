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

######Notes on sucrose gradient
* see: http://www.jove.com/video/51455/polysome-fractionation-analysis-mammalian-translatomes-on-genome-wide
* The 15% → 45% sucrose gradient is made by the Gradient Master machine
  * Fill up tube to top with 45% sucrose and 15% sucrose (half/half)
* Prep machine
  * Level platform with the two nobs
  * Select the only setting available
  * Add sucrose to tube and put black rubber cap on top
  * Press 1
  * Platform start rotating till gradient is created
  * Time/angle/speed shown in top right corner screen
  * Once finished carefully remove magnetic tube holder in a sideways fashion
  * Exit program
  * Turn off
  * Remove top 400 μl of sucrose gradient so you can add lysate
  * Proceed to centrifugation

#####Preparing a sucrose gradient.

1. Prepare ~7 ml of both 45% and 15% sucrose solution per sample by diluting premade 60% sucrose stock solution

Final Conc. | Total vol. | Vol. of 60% Sucrose | Vol. of Polysome buffer
------------|------------|---------------------|------------------------
15% | 15 ml | 3.75 ml | 11.25 ml
45% | 15 ml | 11.25 ml | 3.75 ml
15% | 25 ml | 6.25 ml | 18. 75 ml
45% | 25 ml | 18.75 ml | 6.25 ml

2. Mark the centrifuge tubes iwth the mark block (Thinwall, polyproylene, 13.2 ml, 14 x 89 mm (Beckman)
3. Fill the tubes with 15% sucrose first with the needle and syrnge fill to just slightly above the marked line.
4. Underlay the 45% sucrose slowly to the marked line.
  * Lift the needle up slowly as you add the 45% sucrose to displace the weight
  * Should get a 'bulb at the top of the tube with the 15% sucrose almost spilling over
5. Close off the tube with the black rubber stopper, keeping the air hole at the top during closing
6. Turn on the gradient master and make sure it is level.
7. Place the tubes into the magentic holder and place the holder on the gradient master
8. Use the program: got to gradient -> recent (check this is what you want) -> sw41 -> use -> run
  * if a different gradient is needed, adjust accordingly.
9. While the gradient master is running, clean the needle with methanol and DEPC
10. When gradient is done, remove the stoppers
11. Remove 600 µl of sucrose from the top of the tube with a pipette
12. Gently overlay 550 µl of sample to the top of the gradient.
13. Weigh the tubes and make sure they are balanced to within 0.05 g of each other (add extra sucrose if not).
14. Carefully load the tubes into the SW41 centrifuge rotor
15. Centrifuge at 38,000 rpm for 2 h 38 min at 4ºC.

#####Collecting the fractions

######During the centrifugation, set up the fractionator as follows:

1. Turn on the pump to manual
2. Place the small tubing into 50 ml methanol and reverse pump rapidly into the syringe of the pump.
3. Remove all air bubbles from the syringe and tubing by tilting the machine carefull vertically and forward pump out the bubbles.
4. Connect the needle to the tubing.
5. Slowly pump until methanol comes out of the needle and all of the bubbles are cleared.
6. Turn the bottom of the apparatus to puncture the bottom of the empty sample tube.
  1. Aim to get the needle in the middle of the tube.
  2. Continue puncturing the tube until both black lines on the needle are visible.
7. Pump the methanol into the tube until methanol reaches the waste
8. Remove methanol from the tubing by reverse pumping
9. Transfer methanol back to the 50 ml storage tube.
10. Repeat the above process using DEPC-treated water.

######Fractionating the gradients

1. Prepare ice bucket with premade holes to hold the centrifuge tubes
2. Remove centrifuge tubes with forceps from rotor and place on ice
3. Prepare for fractionation by filling syring with +/- 25 ml of 60% sucrose solution.
4. Attach the seal apparatus on the sample tube.
5. Pump forward at normal speed to remove all bubbles from the needle
6. Place the needle in line with the sample tube until the apparatus is sealed tight.
7. Slowly wind the needle into the sample until both black lines on the needle are visible
8. Check if the graphing machine is warmed up (green light should be on)
9. Remove the cap from the red chart marker
10. Set the needle marker at ~ 30 on the graph.
11. Place Eppendorf tube in the collection platform
12. Turn Brandel pump to "remote"
13. Settings on "forward", "normal", and "1.5"
14. Press run
15. Mark the graph paper as the peaks come out to correspond with the tubes.
16. Label the tubes and place on ice.
17. When profiling is complete or reading to be stopped, go to manual on the Brandel and reverse the sample back.
18. Forward pump into a waste tube.

######Cleaning the fractionator system
1. Remove graph
2. Cap graph marker
3. go back and forth with methanol 3x trough tubing
4. Rinse system with DEPC-treated water 

#####DAY 3
1. Add 500 μl chloroform to both RNA and Riboseq samples
2. Centrifuge 13000 rpm/min, 15min, 4°C
3. Transfer top layer to new Eppendorf
4. Add 500 μl of ice-cold isopropanol 
  1. Add 4 μl of glycogen to Riboseq samples for visualizing pellet
5. Incubate at RT for 10 min (Saisai does 30min)
6. Centrifuge 13000 rpm/min, 15min, 4°C
7. Wash with 70% ethanol (-20°C) 
  1. Shake Eppendorf till pellet floats
  2. Centrifuge 13000 rpm/min, 5min, 4°C
8. Dissolve RNAseq pellet in 10 μl and riboseq in 15 μl MQ H2O
9. Measure concentrations with Nanodrop 2000
  1. Concentrations normally around 1500-2000 ng/μl
  2. If total amount is less than 18 μg, use protocol for low amount RNA
10. Prep Riboseq samples
  1. E.g.: 1531 μg/μl; need ±10 μg
11. So take 7 μl of riboseq sample and add complete to 11 μl with RNAse-free water
12. Store at -80°C
13. Fragmentation of RNAseq samples
  1. Adjust the RNA concentration to 1 μg/μl with RNAse-free water. Set up the following fragmentation in a thin-walled 200 μl PCR tube. Vortex and spin down tube
  2. Reaction: 18 μl of RNA (1 μg/μl), 2 μl fragmentation buffer 10x, 
14. Incubate tube at 94°C for 5 min in thermal cycler block with heated lid on
15. Remove PCR tube from block and immediately add 2 μl of 0.5M EDTA
16. Vortex, spin down, put on ice
  1. In case of low amount of RNA
17. 18 μl of RNA (4 μg total amount of RNA), 2 μl of fragmentation buffer
18. 94°C for 3 min
  1. Repeat previous steps for each batch of five tubes until all RNA has been fragmented
  2. Collect content of all tubes in 1.5 ml eppendorfs and for 400 μl  of fragmentation mixture add 40 μl of 3M sodium acetate (pH 5.2), 4 μl glycogen (100 μg/ml final) and 890 μl of 100% ethanol
  3. Mix content and incubate at -80°C O/N

######Preparing fragmentation buffer:
* 100 µl of 1 M Tris HCl
* 100 µl of 1 M ZnCl2
* 800 µl of RNAse-free water
* Prepare 3 M Sodium acetate, pH 5.2 myself from powder.



