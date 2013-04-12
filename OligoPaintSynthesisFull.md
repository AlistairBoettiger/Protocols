# Part 1 – PCR amplification

## Notes:

We recommend setting up 10 ml of PCR master mix and aliquoting it into a 96-well plate, 100 µl per well. This protocol is scaled for a starting amount of 10 ml; simply scale the volumes in the later sections accordingly if you start with a different scale of PCR. In our hands, this typically results in a final yield of 500 – 2000 nmole of ssDNA FISH probe.

## Reagents:

*   200 µM unlabeled “R” primer stock
*   200 µM labeled “F” primer stock
*   10X PCR buffer (KAPA Buffer A) or equiv.
*   10 mM dNTP mix
*   Molecular biology grade ddH2O
*   1 ng/µl complex DNA library (or 0.01 µM library if working with commercial oligos)
*   Taq DNA polymerase (e.g. KAPA Taq)

## PCR Master Mix:

### Per 100 µl of reaction. Typically 100x for 100uL 96 well plates.

*   10 µl 10x buffer
*   2 µl 10 mM dNTP mix
*   0.5 µl 200 µM “R” unlabeled primer
*   0.5 µl 200 µM “F” labeled primer
*   1 µl 1 ng/µl complex DNA library (or 1 µl 0.01 µM library)
*   1 µl KAPA Taq
*   85 µl ddH2O

## PCR Program

*   “Touch-up” PCR steps (for stepping up library from 21 bp primers to 53 bp secondary-compatiable primers):

1.  95°C 5:00
2.  95°C 0:30
3.  60°C 0:30
4.  72°C 0:15
5.  Repeat 2x (3 cycles total with annealing T of 60°C)

*   Move to the below program
*   (do everything at 60C if using original unextended primers approach)

1.  95°C 0:30
2.  68°C 0:30
3.  72°C 0:15
4.  Repeat 39x (40 cycles total with annealing T of 68°C)
5.  72°C 5:00
6.  End

# Part 2 – DNA precipitation of PCR products

## Reagents:

*   Molecular biology grade glycogen, 20 mg/ml (Thermo #R0561)
*   4 M ammonium acetate (Sigma A1542)
*   Ice-cold 100% ethanol
*   Ice-cold 70% (v/v) ethanol in ddH2O

## Procedure:

1.  Pool the cycled PCR reactions and collect in a 50 ml conical tube

> We find the quickest way to do this is to use a multichannel pipette and a reagent reservoir in a PCR or tissue culture hood.

1.  Add 190 µl of glycogen, 1 ml of 4M ammonium acetate, and 25 ml of ice-cold 100% ethanol. Vortex vigorously

2.  Transfer to 2 ml eppendorf tubes, 2 ml each (~18 tubes)

3.  Incubate at -80°C for 35’ or at -20°C for at least 2 hours

4.  Spin at max speed for 1 hour at 4°C

5.  Aspirate off the supernatant, taking care not to disturb the pellet

6.  Add 1350 µl of ice-cold 70% ethanol to each tube

7.  Spin at max speed for 30 minutes at 4°C

8.  Aspirate off the supernatant, taking care not to disturb the pellet

9.  Air dry the pellets for 15’ on a 42°C heat block

10. Add 40 µl of ddH2O to each tube

11. Incubate at 37°C for 30-60 minutes

12. Proceed to the digestion step directly, else store at 4°C

# Part 3 – Nicking Endonuclease Digestion and Concentration

## Reagents:

*   NEB buffer 2
*   Nb.BsrDI (NEB R0648)

## Procedure:

1.  Pool the precipitated PCR products into one eppendorf tube (~720 µl)

2.  Add 10 µl ddH2O, 90 µl buffer 2, and 80 µl Nb.BsrDI

3.  Vortex the digestion mix and split into PCR strip-tubes, 25 µl per tube (~36 total)

4.  Run the following program in a thermocycler: 65°C for 4 hours -> 80°C for 20 minutes -> 4°C

The digestion products can be left at 4°C or concentrated via precipitation immediately

1.  Pool the digestion reactions (~900 µl), and split 2 x 450 µl into 2 ml eppendorf tubes

2.  To each, add 10 µl of glycogen, 50 µl of 4M ammonium acetate, and 1350 µl of ice-cold 100% ethanol. Vortex vigorously

3.  Incubate for 35’ at -80°C or at -20°C for at least 2 hours

4.  Spin at max speed for 1 hour at 4°C

5.  Aspirate off the supernatant, taking care not to disturb the pellet

6.  Add 1350 µl of ice-cold 70% ethanol to each tube

7.  Spin at max speed for 30 minutes at 4°C

8.  Aspirate off the supernatant, taking care not to disturb the pellet

9.  Air dry the pellets for 15’ on a 42°C heat block

10. Add 60 µl of ddH2O to each tube

11. Incubate at 37°C for 30-60 minutes

12. Proceed to the electrophoresis step directly, else store at 4°C



# Part 4 – Electrophoresis, Gel Extraction, and Recovery

## Notes
Modified to use in-house cast gels and Zhuang Lab equipment.  Original recovery was just to percipitate the extract.  This protocol adds a 1-Butanol extraction to allow a larger volume of water to dissolve gel and reconcentrate product prior to precipitation.  

## Materials:

*   2x Loading Buffer (96% formamide/20mM EDTA, prepare using freshly deionized formamide) 
*   Acrylamide/Bis 19:1 40% (w/v) Solution   
*   TEMED
*   10% APS (w/v). make fresh from powder and store frozen aliquots (<3 months)
*   1-Butanol 

## Procedure:

1.  Prepare 100 mL of acrylamide solution. For a 12% gel:
*   Urea 48 g
*   40% Acrylomide 30 mL
*   10x TBE buffer 10 mL 
*   ddH2O 20 mL
1.  When urea is dissolved, add 150µL of TEMED and 300mL of 10% APS. Mix thoroughly, then pour between gel plates. 
2.  Insert comb, and let gel polymerize for > 45 min. 
3.  Remove sealing tape and insert gel into gel running apparatus. Fill with 0.5x TBE. 
4.  Pre-run gel at 50mA for > 1hr. 
5.  Dissolve the precipitated oligos in 30µL TE and add an equal volume of 2x loading buffer. 
6.  Heat samples for 5 min at 95°C. 
7.  Load samples onto gel and run gel at 50mA. 
8.  Cut out band, crush using pestle, add to a 15mL Falcon tube add 4mL of nuclease free H2O (or TE) then incubate **overnight** at 37°C with shaking. [PAUSE POINT]
9.  Spin down PAGE extraction, save supernatant, and extract gel fragments with an additional 2 mL of nuclease free H2O (or TE) for >2 hrs. 
10. Spin down PAGE extraction and combine with previous supernatant. 
11. Perform butanol extractions 
*   add 3 volumes of 1-BuOH to the sample, 
*   vortex to mix, 
*   spin briefly to separate layers (1000 RPM 30s), 
*   discard organic [top] layer (butanol-waste). 
*   Repeat until the volume is < 300 µL. 
1.  If residual polyacrylamide fragments are present, centrifuge aqueous layer to remove gel fragments. 
2.  Ethanol precipitate the DNA: 
*   add 1/10 volumes of 3M NaOAc, mix, 
*   add 2.5 volumes (including the NaOAc) ice-cold EtOH.
*   Incubate at -20°C for > 30 min, then spin for 30 min at max speed in cold room.
*   Pour off supernatant, add 0.5 mL of ice-cold 80% EtOH to pellet, spin for 5 min at room temp, and pour off supernatant.
*   Dry pellet by air drying (15’ on a 42°C heat block) or using the speed vac. Do not overdry single-stranded DNA (may degrade).
15. Resuspend in 60 µl of ddH2O, incubate at 37°C for 30-120 minutes
16. Quantify probe yield by spectrophotometry using a fluorometer or Nanodrop (microarray setting) on the fluorophore (i.e. read out pmoles/µl of fluor).

