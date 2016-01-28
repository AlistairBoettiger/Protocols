## Rapid Oligo Probe Synthesis

### Limited Cycle PCR (50 uL)
1. Prepare on ice:
 * 20 uL ddH2O
 * 25 uL Phusion Master Mix
 * 2 uL Fwd primer (10 uM)
 * 2 uL Rev-T7 primer (10 uM)
 * 1 uL library (1:50 dilution)
 * 2.5 uL 20x EvaGreen (Biotium)
2. Run reaction on QPCR machine, stop reactions for each tube while amplification is still in the exponential growth phase (before it reaches the saturation phase).  A calibration run may be necessary first to identify when this will happen.
3. **Recommended:** Test PCR by running 2 uL out on a 2% agarose Na Borax gel.  Use gel green spiked 6x orange loading dye. There should only be a single band if the reaction does not saturate. 

### PCR cleanup
1. in a 1.5 uL tube, add 350 uL Zymo DNA binding buffer to 50 uL of PCR product
2. Transfer to a zymo DCC-5 column, spin at >10,000g, 30s
3. Add 200 uL DNA Wash Buffer to column, spin at >10,000g, 30s
4. Repeat the wash step.
5. Discard flow-through by aspirating dry the collection tube. Then spin at >10,000g 1 min to remove residual buffer.
6. Transfer column to clean 1.5 mL tube and elute DNA in 11 uL ddH2O

###  T7 reaction (~20 uL)
1. Prepare on ice in RNase free environment:
  * 10 uL DNA from PCR 
  * 2 uL each: ATP, CTP, GTP, UTP
  * 2uL T7 reaction buffer (NEB T7 High Yield kit)
  * 2uL T7 Pol Mix (NEB T7 High Yield kit)
  * 1 uL RNasin Plus (RNase inhibitor)
2. Incubate at 37C for 16 hrs.

### RT reaction (~20 uL)
1. Prepare on ice in RNase free environment:
 * 2 uL dNTPs
 * 4 uL RT buffer
 * 4 uL 100 uM labeled primer 
 * 1 uL or less Maxima RT enzyme
 * 1 uL RNasin Plus (RNase inhibitor)
 * 10 uL RNA from T7 reaction 
2. Incubate at 50C for 1 hour.  (No pre-denaturing step).
3. Digest remaining RNA 
    * mix 1:1 0.5 M EDTA and 1 M NaOH.  Add 20 uL per sample
    * Heat at 95C for 10 min 
4. **Recommended:** Test RT by running 2 uL out on a 15% urea TBE gel.  Use urea loading buffer. 
5. **NOTE:** This can be scaled up to 1-2 nmol of labeled primer if all 20-30uL of RNA is used and concentrations and volume are adjusted accordingly (50-100 uL reaction).  

### Probe Cleanup

1. add 80 uL Oligo Binding buffer to each tube (2x the volume of sample) and mix.
2. Transfer the mix to a 1.5 mL tube containing 320 uL of 100% EtOH and mix.
3. Transfer the solution to a DCC-25 column (can reuse, see below*), spin to elute and discard flow-through.
4. Add 750 uL DNA Wash Buffer.  Spin at >10,000g and discard flow through.
5. Spin column to remove excess buffer
6. Transfer column to clean 1.5 uL tube and elute in 30 uL ddH2O.
7. Measure final probe concentration
8.  **NOTE:** Use Zymo DCC-100 columns if using a larger scale RT prep (1 nmol or more of primer).  Elute in 100 uL and concentrate sample using seedVac.

*You can use the same columns you used to clean up the PCR as long as you haven't mixed them up.  I recommend running 700 uL of ddH2O through the column first just to elute any last residual DNA.